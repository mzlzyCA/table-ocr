---
name: table-ocr
version: 0.2.1
description: >
  OCR tables from scanned documents, images, photos, and screenshots using MinerU-powered recognition. Extract tabular data from non-digital sources into structured formats like CSV, Excel, Markdown, and JSON.

  表格OCR识别, 扫描表格提取, 图片表格识别, 表格数据提取, 扫描件表格OCR, 文档表格识别.

  Synonyms: table recognition, table detection, scanned table extraction, image table OCR, table digitization, tabular data OCR, document table recognition, spreadsheet OCR, table image parser, table structure recognition, optical table recognition, scan-to-table converter.

  Use when asked to "OCR this table", "extract table from image", "read table from scanned document", "digitize this printed table", "convert scanned table to spreadsheet", "I have a photo of a table I need as data", "recognize tables in this scan", "pull data from this table image", "can you read this table from a screenshot", "turn this paper table into CSV".

  Solves problems like: scanned documents with tables that aren't searchable, photos of printed tables that need to be editable, table data trapped in images, manual re-typing of table data, need structured data from physical documents, batch processing scanned tables.

  Powered by MinerU for high-accuracy table structure recognition and cell content extraction.
tags:
  - ocr
  - table
  - scanning
  - image-recognition
  - data-extraction
  - csv
  - excel
  - mineru
  - table-detection
  - digitization
  - document-processing
---

# Table OCR

Use the MinerU tool to recognize and extract tables from scanned documents and images.

## Instructions

1. When the user provides a scanned document or image containing tables, use the mineru tool to perform OCR and extract table data.
2. Output the extracted table in the user's preferred format (Markdown, CSV, JSON, etc.).
3. If the mineru tool encounters an error, report it clearly and suggest alternatives (check image quality, ensure file is accessible).
4. Handle edge cases: low-resolution images, rotated scans, complex merged cells, multi-page tables.
