# PicassoPDF — HTML to PDF Converter API

![PicassoPDF](https://img.shields.io/badge/PicassoPDF-HTML--to--PDF%20API-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![npm](https://img.shields.io/npm/v/picassopdf)

**HTML to PDF converter API for SaaS, fintech, and healthtech. Convert URLs or HTML to PDF, generate invoices, bank statements, medical reports, and automate document workflows with our REST API or SDK.**

---

## 🚀 Features

- Convert **HTML or URLs to PDF programmatically**  
- **Batch HTML-to-PDF API** for high-volume document generation  
- **PDF generator for developers** with REST API & SDK support  
- Multi-language support: **Node.js, Python, PHP, Java, C#**  
- **Secure PDF generation API** for compliance-friendly documents  
- Generate **invoices, receipts, bank statements, and medical reports**  
- Lightweight, fast, and easy to integrate into SaaS, fintech, and healthtech workflows  

---

## 🔑 Use Cases

- **Invoice PDF generator API** – automate invoices for SaaS & eCommerce  
- **Receipt PDF generator** – generate receipts for online payments  
- **Financial report PDF API** – convert bank statements & accounting data  
- **Medical report PDF generator** – export patient records securely  
- **Compliance PDF generator** – generate audit-ready PDFs  
- **Document automation PDF API** – integrate PDF generation into workflows  

---

## ⚡ Installation + Code Examples
**For batch conversions simply pass an array with urls strings inside**

**Node.js:**
npm install picassopdf

const PicassoPDF = require('picassopdf');

const pdf = new PicassoPDF();
pdf.convert('https://example.com').toPDF('output.pdf')
  .then(() => console.log('PDF generated!'))
  .catch(err => console.error(err));

**Python:**
pip install picassopdf

pdf = PicassoPDF()
pdf.convert("https://example.com").to_pdf("output.pdf")

**Java:**
import com.picassopdf.PicassoPDF;

public class PdfExample {
    public static void main(String[] args) {
        PicassoPDF pdf = new PicassoPDF();
        try {
            pdf.convert("https://example.com")
               .toPDF("output.pdf");
            System.out.println("PDF generated!");
        } catch (Exception e) {
            e.printStackTrace();
        }
    }
}

**C#:**
using PicassoPDF;

class Program
{
    static void Main()
    {
        var pdf = new PicassoPDF.PicassoPDF();
        try
        {
            pdf.Convert("https://example.com").ToPDF("output.pdf");
            Console.WriteLine("PDF generated!");
        }
        catch (Exception ex)
        {
            Console.WriteLine(ex.Message);
        }
    }
}

**PHP:**
<?php
require 'vendor/autoload.php';

use PicassoPDF\PicassoPDF;

$pdf = new PicassoPDF();
try {
    $pdf->convert("https://example.com")->toPDF("output.pdf");
    echo "PDF generated!";
} catch (Exception $e) {
    echo "Error: " . $e->getMessage();
}
?>

---

## 📄 Documentation

- [Full API Documentation](https://picassopdf.com/docs)  
- [SDKs & Integration Guides](https://picassopdf.com/docs/sdk) 

---

## 🌐 Supported Platforms & Languages

Node.js / JavaScript
Python
PHP
Java
C#
REST API (platform-agnostic)

---

## 💡 Why Choose PicassoPDF?
Designed for developers needing high-quality, programmatic PDF generation
Optimized for batch PDF processing
Supports HTML, CSS, JS rendering in PDFs
Perfect for SaaS, fintech, and healthtech applications
Lightweight, fast, secure, and reliable

---

## 📝 License
MIT License © 2025 PicassoPDF

