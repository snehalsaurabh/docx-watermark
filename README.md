**docx-watermark** is an open-source library for programmatically adding watermarks to Microsoft Word `.docx` documents.

The library provides a robust implementation built directly on the WordprocessingML specification rather than relying on template extraction or document conversion. It safely inserts watermark shapes into document headers while preserving the original structure, formatting, and relationships inside the DOCX file.

Unlike many existing solutions that require commercial licensing or external office software, docx-watermark is designed to be lightweight, dependency-minimal, and fully open source.

## Features
- Add text watermarks to .docx documents
- Control watermark opacity and rotation
- Apply watermarks across all document sections
- Preserve existing document formatting and layout
- Fully programmatic implementation based on the OpenXML Wordprocessing specification

## Design Goals
- Reliability and compatibility with Microsoft Word
- Clean, extensible architecture for future features
- Zero dependency on Microsoft Office installations
- Fully open-source and free to use

## Planned Features
- Image watermark support
- Page range targeting
- Watermark tiling and positioning controls
- CLI interface
- Support for PDF watermarking
