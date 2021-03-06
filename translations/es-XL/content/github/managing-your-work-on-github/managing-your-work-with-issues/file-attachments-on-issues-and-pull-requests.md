---
title: File attachments on issues and pull requests
intro: 'When you open issue or update a pull request, you can use issue attachments to upload images of proposed features or screenshots of bugs.'
redirect_from:
  - /articles/issue-attachments/
  - /articles/file-attachments-on-issues-and-pull-requests
  - /github/managing-your-work-on-github/file-attachments-on-issues-and-pull-requests
versions:
  free-pro-team: '*'
  enterprise-server: '*'
  github-ae: '*'
topics:
  - Pull requests
---
{% warning %}

**Warning:** If you add an image to a pull request or issue comment, anyone can view the anonymized image URL without authentication, even if the pull request is in a private repository{% if currentVersion != "free-pro-team@latest" %}, or if private mode is enabled{% endif %}. To keep sensitive images private, serve them from a private network or server that requires authentication. {% if currentVersion == "free-pro-team@latest" %}For more information on anonymized URLs see "[About anonymized image URLs](/articles/about-anonymized-image-urls)".{% endif %}

{% endwarning %}

To attach a file to an issue or pull request conversation, drag and drop it into the comment box. Alternatively, you can click the bar at the bottom of the comment box to browse, select, and add a file from your computer.

![Select attachments from computer](/assets/images/help/pull_requests/select-bar.png)

{% tip %}

**Tip:** If you're using Chrome, you can also copy-and-paste images directly into the box.

{% endtip %}

The maximum size for files is 25MB and the maximum size for images is 10MB.

We support these files:

* PNG (*.png*)
* GIF (*.gif*)
* JPEG (*.jpg*)
* Log files (*.log*)
* Microsoft Word (*.docx*), Powerpoint (*.pptx*), and Excel (*.xlsx*) documents
* Text files (*.txt*)
* PDFs (*.pdf*)
* ZIP (*.zip*, *.gz*)

![Attachments animated GIF](/assets/images/help/pull_requests/dragging_images.gif)
