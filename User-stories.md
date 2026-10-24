# User Stories

1. As a user, I want to upload an image of a Quranic verse, so that I can check if the text in the image is authentic. (FR1, FR5)

Acceptance Criteria:
  - System accepts JPEG/PNG files up to 5MB.
  - Displays clear error message if invalid file format is uploaded.
     
2. As a researcher, I want the system to highlight missing or incorrect Arabic diacritics, so that I can see exact differences between the image and the reference text. (FR3, FR4,FR5)

Acceptance Criteria:
  - Extracted text is displayed side-by-side with verified reference text.
  - Mismatched diacritics are visually highlighted.

3. As a student, I want to receive an immediate similarity percentage score, so that I know the confidence level of the match without manual checking. (FR4, FR5)

Acceptance Criteria:
  - Match score is displayed clearly as a percentage like 95% Match.
  - System identifies and outputs the matching Ayah number.
