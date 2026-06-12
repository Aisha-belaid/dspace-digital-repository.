# Al-Mergib University Digital Library & Repository System

An institutional, secure, and high-performance digital repository and central library management system custom-built for the Faculty of Science at Al-Mergib University. This platform serves to preserve, index, and provide open access to academic research, scientific theses, and digital library assets.

## 🏛️ Project Context
This digital ecosystem was designed and implemented to modernize the central library infrastructure of the Faculty of Science at Al-Mergib University, enabling seamless digital asset management, localized metadata configurations, and academic archiving.

## 🚀 Key Features
* Advanced Archiving & Preservation: Secure ingestion and long-term storage of digital academic papers, books, and graduate student theses.
* High-Performance Search & Indexing: Powered by Apache Solr for lightning-fast faceted searching, metadata indexing, and precise title/subject retrieval.
* Responsive UI/UX Bootstrap Layout: A modern, fully customized interface tailored specifically for Al-Mergib University branding, built with Bootstrap to support seamless fluid layouts across all mobile and desktop screens.
* Hybrid System Integration: Incorporates specialized tools and sub-systems to optimize the extraction and handling of library records.

## 🛠️ Technology Stack
* Core Framework: DSpace 6.3 (Source Release Architecture)
* Backend & System Logic: Java & C# (.NET Integration Components)
* Build Tools & Automation: Apache Maven & Apache Ant
* Database Layer: MySQL Database
* Search Engine & Indexing: Apache Solr
* Web Server Container: Apache Tomcat
* Frontend Framework: Bootstrap (HTML5 / CSS3 / JavaScript)
* Specialized Utilities: Advanced Program Configuration

## 📂 Repository Structure & Management
The project incorporates customized theme overrides and localized schema layouts:
* /dspace - Main installation, command-line utilities, and configuration tree.
* /dspace-api - Backend core APIs, Java logic, and database integrations.
* /csharp-modules - Custom C# utilities for advanced metadata parsing and system tools.
* /dspace-xmlui - Bootstrap-integrated responsive user interface layers.

## 🔧 Deployment & Quick Start
To build and deploy this repository infrastructure locally:

1. Prerequisites: Ensure Java JDK, .NET Runtime (for C# components), Apache Maven, Apache Ant, MySQL, and Apache Tomcat are installed.
2. Database Setup: Configure your MySQL database instance and run the initial repository schemas.
3. Build the Source Package:
`bash
   mvn package
