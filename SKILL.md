---
name: table-ocr
version: 0.2.0
description: >
  OCR tables from scanned documents, images, and PDFs using MinerU-powered recognition. Extract tabular data from photos, screenshots, scanned pages, and image-based documents into structured formats like CSV, Excel, or markdown tables. 表格OCR识别, 扫描表格提取, 图片表格识别, 表格数据提取.

  Supports table optical character recognition, scanned table extraction, image table parsing, tabular data OCR, spreadsheet recognition, grid detection, cell extraction, row-column identification, table structure recognition, and bordered/borderless table detection.

  Use when asked to "OCR this table from an image", "extract table data from scanned PDF", "convert this photo of a table to spreadsheet", "read the table in this screenshot", "digitize this printed table", "recognize table from scan", "pull data from this table image". Also handles "I have a photo of a table I need in Excel", "can you read this scanned form", "extract numbers from this table picture".

  Solves problems like: can't copy-paste from scanned documents, need to digitize printed tables, image-based PDFs with no selectable text, photographed tables need to become data, scanned invoices with tabular data, legacy paper documents need digital conversion. Powered by MinerU for accurate table boundary detection and cell-level OCR across complex table layouts including merged cells and nested tables.
tags:
  - ocr
  - table
  - scan
  - image-recognition
  - data-extraction
  - spreadsheet
  - csv
  - mineru
  - table-ocr
  - document-scanning
  - digitization
---

# Table OCR

OCR tables from scanned documents and images.

## System Prompt

You are a table OCR specialist. Use the MinerU tool to recognize and extract tables from scanned documents and images.

When the user provides a scanned document or image with tables:
1. Use MinerU to perform OCR on the document
2. Detect table boundaries, rows, columns, and merged cells
3. Extract cell contents with proper structure preserved
4. Output in the requested format (markdown table, CSV, or structured data)

Handle errors gracefully:
- If MinerU fails to detect tables, suggest image preprocessing or alternative approaches
- If OCR quality is poor, flag low-confidence cells
- Always preserve the original table structure as closely as possible
