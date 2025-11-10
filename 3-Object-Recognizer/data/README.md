# Image Data Folder

This folder is designated for image files used in the Object Recognizer module.

## Required Files

Please add the following image files to this folder:
- `image1.jpg`
- `image2.jpg`

## Instructions

1. Download or obtain sample images
2. Rename them to `image1.jpg` and `image2.jpg`
3. Place them in this directory

**File Format**: The files **must be named** `image1.jpg` and `image2.jpg`, but the actual format can be JPG, JPEG, or PNG. The Pillow library will automatically detect and handle these formats. Just ensure the filename ends with `.jpg` as the notebook code looks for that specific extension.

**Important**: Use images with **different subjects/categories** to demonstrate the model's versatility. For example:
- `image1.jpg` could contain people and vehicles
- `image2.jpg` could contain animals and furniture

## Image Recommendations

For best results with the object detection model, use images that contain:
- Common everyday objects (people, cars, animals, furniture, etc.)
- Clear, well-lit subjects
- Multiple objects for more interesting detection results
- **Different categories between image1 and image2** to showcase the model's broad detection capabilities

## Note

The notebook will display an error message if these files are not found. The error handling in the notebook will guide you if the images are missing.
