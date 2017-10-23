---
layout: page-fullwidth
title: "Collections data request form"
permalink: "/request-form"
---

<html>
<body>
<form action="https://formspree.io/dlp-staff@library.ucla.edu" method="POST">
Name:<br>
<input type="text" name="name" required><br>
E-mail:<br>
<input type="text" name="mail" required><br>
Collection URL:<br>
<input type="text" name="url" size="200" required><br>
Content: <br>
<select name="content" required>
  <option value="" disabled selected>Choose Option</option>
  <option value="metadata" name="metadata">Metadata</option>
  <option value="images" name="images">Images</option>
  <option value="both" name="both">Metadata and Images</option>
</select>
Date needed by: <br><input type="date" name="neededby" required>
Purpose: <br>
<select name="purpose" required>
  <option value="" disabled selected>Choose Option</option>
  <option value="teaching" name="teaching">Teaching</option>
  <option value="research" name="research">Research</option>
  <option value="learning" name="learning">Learning</option>
  <option value="other" name="other">Other</option>
</select>
Please briefly describe your need/project:<br>
<input type="text" name="url" size="100"><br><br>
<input type="hidden" name="_next" value="/resources" />
<input type="submit" value="Send">
</form>
</body>
</html>