# Uncommon HTML Bug: Object Tag and PDF Rendering

This repository demonstrates an uncommon HTML bug related to the use of the `&lt;object&gt;` tag for embedding PDFs.  The problem arises when the `type` attribute is missing or specifies an incorrect MIME type, preventing the browser from correctly rendering the embedded PDF.

This is less common than typical HTML errors like missing closing tags or incorrect nesting, making it a more subtle and harder-to-debug issue.

The `bug.html` file shows the problematic code. The `bugSolution.html` file provides the corrected code and demonstrates a proper usage for `&lt;object&gt;` tag.

## Bug Description

The `&lt;object&gt;` tag fails to render the embedded PDF because the `type` attribute is either missing or incorrect.  This leads to inconsistent results across different browsers and could be challenging for developers to diagnose without specific knowledge of MIME types.