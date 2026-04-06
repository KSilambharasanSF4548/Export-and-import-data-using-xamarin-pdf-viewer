# Export-and-import-data-using-xamarin-pdf-viewer
This repository contains the sample that demonstrates exporting/importing of annotations and form data using Xamarin PDF Viewer
## Overview
This repository contains Xamarin sample applications that demonstrate how to export and import annotations and form field data using the Xamarin PDF Viewer. The samples are intended to help developers understand how to persist user interactions with PDF documents and restore them when needed, without modifying the original PDF file.
PDF documents often include interactive elements such as annotations (highlights, shapes, text notes, ink drawings) and form fields (text boxes, checkboxes, radio buttons, and signatures). This repository focuses on showing how these elements can be extracted, saved externally, and reapplied to the same or another PDF document later.
These techniques are useful for maintaining document state across app restarts, syncing data between devices, or sharing user-generated content in collaborative workflows.

### Export and Import Annotations
The annotation sample demonstrates how users can add annotations to a PDF document loaded in the Xamarin PDF Viewer and then export those annotations programmatically. The exported annotation data can be saved as a file or stream and stored locally or remotely.
The import functionality allows the previously exported annotation data to be reapplied to the PDF document. Once imported, all annotations appear in their original positions with the same properties, such as color, size, opacity, and type.
This workflow is commonly used in document review systems, feedback applications, and collaborative platforms where annotations need to be preserved or shared.

### Export and Import Form Data
The form data sample focuses on working with interactive PDF form fields. Users can fill out form fields within the PDF Viewer, and the application can export the entered values independently of the PDF document.
Exported form data can later be imported back into the PDF Viewer to automatically populate the corresponding fields. This allows applications to save partially completed forms, restore form values after restarting the app, or transfer form data across devices.
This scenario is particularly useful for business forms, surveys, applications, and any workflow where PDF forms are used for data collection.

### Key Capabilities Demonstrated

Integrating Xamarin PDF Viewer into mobile applications
Exporting PDF annotations created by users
Importing previously saved annotations
Exporting PDF form field values
Importing form data and auto-filling form fields
Preserving user input across sessions
Working with PDF streams and external storage


### Prerequisites
To run and understand these samples, you should have:

Visual Studio with Xamarin development support
Basic knowledge of Xamarin (Android, iOS, or Forms)
Xamarin PDF Viewer configured in the project
A supported mobile platform (Android or iOS)

### Additional Notes

The original PDF document remains unchanged during export and import operations
Annotation and form data can be stored in files, databases, or transmitted over a network
These samples are designed for learning and demonstration purposes


## Conclusion
This repository provides practical examples of how to implement annotation and form data persistence in Xamarin applications using the PDF Viewer. By following these samples, developers can build robust applications that retain user interactions with PDF documents and deliver a smooth, reliable document experience.
