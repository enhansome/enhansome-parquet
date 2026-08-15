# Awesome Parquet with stars

[![Parquet Logo](assets/logo.svg)](https://parquet.apache.org/)

> Open-source resources for using the Parquet format. This list only includes resources for the generic Parquet format. If you are looking for GeoParquet resources (tools, libraries, data providers), please check out [geoparquet.org](https://geoparquet.org/#implementations).

## Contents

* [Libraries](#libraries)
  * [C GLib](#c-glib)
  * [C++](#c)
  * [Dart](#dart)
  * [Go](#go)
  * [Java](#java)
  * [JavaScript](#javascript)
  * [Julia](#julia)
  * [.NET](#net)
  * [PHP](#php)
  * [Python](#python)
  * [R](#r)
  * [Ruby](#ruby)
  * [Rust](#rust)
  * [Swift](#swift)
  * [VBA](#vba)
* [Tools](#tools)
  * [Command-line](#command-line)
  * [Desktop applications](#desktop-applications)
  * [Plugins and extensions](#plugins-and-extensions)
  * [Terminal UI](#terminal-ui)
  * [Web](#web)
* [Resources](#resources)
  * [Blogs](#blogs)
  * [Documentation](#documentation)
  * [Educative resources](#educative-resources)
  * [Parquet engineering](#parquet-engineering)
  * [Tests](#tests)
* [Related formats](#related-formats)

## Libraries

### C GLib

* [Arrow GLib](https://arrow.apache.org/docs/c_glib/parquet-glib/index.html) - A wrapper library for Arrow C++.
* [DuckDB](https://duckdb.org/docs/stable/clients/c/overview) - An in-process database library that supports reading and writing Parquet files.

### C++

* [Apache Arrow C++](https://github.com/apache/arrow/tree/main/cpp) ⭐ 17,026 | 🐛 2,558 | 🌐 C++ | 📅 2026-08-14 - A library with support for reading and writing Parquet files.
* [DuckDB C++ API](https://duckdb.org/docs/stable/clients/cpp) - Internal DuckDB C++ API.
* [libcudf](https://docs.rapids.ai/api/cudf/stable/libcudf_docs/) - A GPU-accelerated DataFrame library for tabular data processing.

### Dart

* [DuckDB.Dart](https://duckdb.org/docs/stable/clients/dart) - DuckDB Dart bindings.

### Go

* [duckdb-go](https://duckdb.org/docs/stable/clients/go) - DuckDB Go client.
* [parquet](https://pkg.go.dev/github.com/apache/arrow-go/v18/parquet) - Official Go implementation of Apache Arrow.
* [parsyl/parquet](https://github.com/parsyl/parquet) ⭐ 127 | 🐛 2 | 🌐 Go | 📅 2025-04-17 - A Go library for reading and writing Parquet files.

### Java

* [cudf](https://github.com/rapidsai/cudf/tree/main/java) ⭐ 9,730 | 🐛 1,325 | 🌐 C++ | 📅 2026-08-15 - Java bindings for cudf, to be able to process large amounts of data on a GPU.
* [parquet-java](https://github.com/apache/parquet-java) ⭐ 3,073 | 🐛 722 | 🌐 Java | 📅 2026-08-15 - A Java implementation of the Parquet format, owned by the Apache Software Foundation.
* [hardwood](https://github.com/hardwood-hq/hardwood) ⭐ 356 | 🐛 217 | 🌐 Java | 📅 2026-08-15 - A minimal dependency implementation of Apache Parquet.
* [parquet-carpet](https://github.com/jerolba/parquet-carpet) ⭐ 95 | 🐛 2 | 🌐 Java | 📅 2026-08-15 - A Java library for serializing and deserializing Parquet files efficiently using Java records.
* [duckdb-java](https://duckdb.org/docs/stable/clients/java) - DuckDB Java/JDBC API.

### JavaScript

* [lakeql](https://github.com/earonesty/lakeql) ⭐ 8 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-10 - Pure JavaScript duck-compatible SQL query engine for Parquet and Iceberg data in object storage.
* [duckdb-node-neo](https://duckdb.org/docs/stable/clients/node_neo/overview) - DuckDB Node.js client.
* [duckdb-wasm](https://duckdb.org/docs/stable/clients/wasm/overview) - WebAssembly version of DuckDB.
* [hyparquet](https://github.com/hyparquet/hyparquet) - A lightweight, dependency-free, pure JavaScript library for parsing Apache Parquet files.
* [parquet-wasm](https://kylebarron.dev/parquet-wasm/) - WebAssembly bindings to read and write the Apache Parquet format to and from Apache Arrow using the Rust parquet and arrow crates.

### Julia

* [DuckDB](https://duckdb.org/docs/stable/clients/julia) - Official DuckDB Julia package.
* [Parquet.jl](https://github.com/JuliaIO/Parquet.jl) ⭐ 128 | 🐛 36 | 🌐 Julia | 📅 2026-01-25 - Julia implementation of Parquet columnar file format reader.

### .NET

* [Parquet.Net](https://github.com/aloneguid/parquet-dotnet) ⭐ 902 | 🐛 35 | 🌐 C# | 📅 2026-08-11 - A fully managed Parquet library for .NET.
* [ParquetSharp](https://g-research.github.io/ParquetSharp/) - A .NET wrapper over the C++ Parquet library that integrates with [.NET Arrow](https://github.com/apache/arrow-dotnet) ⭐ 35 | 🐛 46 | 🌐 C# | 📅 2026-08-10.

### PHP

* [duckdb-php](https://duckdb.org/docs/stable/clients/php) - DuckDB API for PHP.

### Python

* [duckdb-python](https://duckdb.org/docs/stable/clients/python/overview) - DuckDB Python client.
* [fastparquet](https://github.com/dask/fastparquet/) ⭐ 901 | 🐛 97 | 🌐 Python | 📅 2026-06-29 - A Python implementation of the Parquet columnar file format.
* [pyarrow](https://arrow.apache.org/docs/python/parquet.html) - A Python API for functionality provided by the Arrow C++ libraries, along with tools for Arrow integration and interoperability with Pandas, NumPy, and other software in the Python ecosystem.
* [pylibcudf](https://docs.rapids.ai/api/cudf/stable/pylibcudf/) - A lightweight Cython interface to libcudf that provides near-zero overhead for GPU-accelerated data processing in Python.
* [rugo](https://rugo.dev/) - A lightweight, dependency-free Python library for Apache Parquet files.

### R

* [arrow](https://arrow.apache.org/docs/r/articles/arrow.html) - The `arrow` package provides an Arrow C++ backend to `dplyr`, and access to the Arrow C++ library through familiar base R and tidyverse functions, or `R6` classes.
* [duckdb-r](https://duckdb.org/docs/stable/clients/r) - DuckDB R package.
* [nanoparquet](https://nanoparquet.r-lib.org/) - A reader and writer for a common subset of Parquet files.

### Ruby

* [Red Parquet](https://github.com/apache/arrow/tree/main/ruby/red-parquet) ⭐ 17,026 | 🐛 2,558 | 🌐 C++ | 📅 2026-08-14 - The Ruby bindings of Apache Parquet, based on GObject Introspection.

### Rust

* [datafusion](https://datafusion.apache.org) - An extensible query engine written in Rust that can read/write Parquet files using SQL or a DataFrame API.
* [duckdb-rs](https://duckdb.org/docs/stable/clients/rust) - DuckDB Rust client.
* [parquet](https://arrow.apache.org/rust/parquet/index.html) - The official Native Rust implementation of Apache Parquet, part of the Apache Arrow project.
* [Polars](https://github.com/pola-rs/polars) ⭐ 39,361 | 🐛 2,838 | 🌐 Rust | 📅 2026-08-14 - A DataFrame interface on top of an OLAP Query Engine that supports reading and writing Parquet files, with bindings for Python.

### Swift

* [duckdb-swift](https://duckdb.org/docs/stable/clients/swift) - DuckDB Swift client.

### VBA

* [duckdb-vba](https://github.com/EtienneLenoir/duckdb-vba) ⭐ 9 | 🐛 0 | 🌐 VBA | 📅 2026-06-11 - Excel/VBA bridge for DuckDB, enabling users to read, query, transform, and export Parquet files directly from Excel through a native DLL bridge.

## Tools

### Command-line

* [parquet-cli](https://github.com/apache/parquet-java/tree/master/parquet-cli) ⭐ 3,073 | 🐛 722 | 🌐 Java | 📅 2026-08-15 - Java-based CLI tool for exploring parquet files.
* [ODBC to Parquet](https://github.com/pacman82/odbc2parquet) ⭐ 256 | 🐛 3 | 🌐 Rust | 📅 2026-08-10 - A command-line tool to query an ODBC data source and write the result into a parquet file.
* [nail](https://github.com/Vitruves/nail-parquet) ⭐ 97 | 🐛 1 | 🌐 Rust | 📅 2026-07-12 - Command-line tool for analyzing, transforming, and exploring data files.
* [parquet-cli-standalone](https://github.com/marcelmay/parquet-cli-standalone) ⭐ 5 | 🐛 1 | 🌐 Java | 📅 2026-07-27 - A JAR file for the parquet-cli tool which can be run without any dependencies.
* [parquet-grep](https://github.com/hyparam/parquet-grep) ⭐ 2 | 🐛 1 | 🌐 JavaScript | 📅 2025-12-17 - A CLI tool to search for strings in Parquet files.
* [Agentsor File Contracts](https://github.com/linkoinsight/agentsor-file) ⚠️ Archived - Python CLI for checking a Parquet file against an explicit TOML contract.
* [DataFusion CLI](https://datafusion.apache.org/user-guide/cli/overview.html) - A single, dependency-free executable that can read and write Parquet files, with a SQL interface.
* [DuckDB CLI](https://duckdb.org/docs/stable/clients/cli/overview.html) - A single, dependency-free executable that can read and write Parquet files, with a SQL interface.
* [parquet-tools](https://pypi.org/project/parquet-tools/) - Python-based CLI tool for exploring parquet files (part of Apache Arrow).
* [Spark](https://spark.apache.org/) - A multi-language engine for executing data engineering, data science, and machine learning on single-node machines or clusters.

### Desktop applications

* [Munquet](https://gitlab.com/zulfian1732/munquet) - A desktop tool to convert CSV files to Parquet.
* [Pink Parquet](https://pinkparquet.com/) - A free and open-source, user-friendly viewer for Parquet files for Windows.
* [Tad](https://github.com/antonycourtney/tad) ⭐ 3,475 | 🐛 166 | 🌐 TypeScript | 📅 2025-03-05 - An application for viewing and analyzing tabular data sets.

### Plugins and extensions

* [KoldStore](https://github.com/kalamdb/koldstore) ⭐ 5 | 🐛 52 | 🌐 Rust | 📅 2026-08-13 - PostgreSQL tiered storage that moves historical rows to Parquet while keeping the original table fully queryable and supporting updates and deletes.
* [nf-parquet](https://github.com/nextflow-io/nf-parquet) ⭐ 4 | 🐛 1 | 🌐 Groovy | 📅 2026-03-14 - A Nextflow plugin able to read and write parquet files.

### Terminal UI

* [Tabiew](https://github.com/shshemi/tabiew) ⭐ 3,076 | 🐛 15 | 🌐 Rust | 📅 2026-08-15 - A lightweight TUI application to view and query tabular data files, such as CSV, TSV, and parquet.
* [parqeye](https://github.com/kaushiksrini/parqeye) ⭐ 675 | 🐛 19 | 🌐 Rust | 📅 2026-07-23 - Peek inside Parquet files right from your terminal.
* [Datanomy](https://github.com/raulcd/datanomy) ⭐ 431 | 🐛 15 | 🌐 Python | 📅 2026-05-21 - A terminal-based tool for visualizing a Parquet file's metadata and structure.
* [parquetlens](https://github.com/cfahlgren1/parquetlens) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-13 - Parquet previewer with a csvlens-style TUI.
* [DataTUI](https://www.datatui.io/) - A keyboard-first terminal UI for exploring Parquet with tabs, sorting, filtering, SQL (Polars), and more.

### Web

* [Datasette](https://lite.datasette.io/) - A tool to explore datasets, with support for reading Parquet files.
* [DataStudio](https://github.com/dataspren-analytics/datastudio) ⭐ 78 | 🐛 7 | 🌐 TypeScript | 📅 2026-03-12 - Explore and visualize data, entirely in your browser.
* [GeoParquet Viewer](https://geoparquet.info/) - A table and map viewer for Parquet files in the browser.
* [Onyxia Data Explorer](https://datalab.sspcloud.fr/data-explorer) - A web-based tool to explore Parquet files in the browser.
* [Parquet File Visualizer](https://julien.ledem.net/experiment/parquet-visualizer.html) - Claude-code generated parquet metadata visualizer that runs in your browser.
* [Parquet Viewer](https://parquet-viewer.xiangpeng.systems/) - View parquet files online.
* [ParquetKit](https://parquetkit.com) - View, query with SQL, and convert Parquet files entirely in the browser, powered by DuckDB-Wasm and hyparquet.
* [Quak](https://manzt.github.io/quak) - A scalable data profiler for quickly scanning large tables.

## Resources

### Blogs

* [icem7](https://www.icem7.fr/?s=parquet) - Un blog sur les outils de data science, avec des articles de fond sur Parquet.
* [Hyparquet: The Quest for Instant Data](https://blog.hyperparam.app/2025/07/24/quest-for-instant-data/) - 6 optimization tricks to read Parquet files faster in the browser.
* [Querying Parquet with Precision Using DuckDB](https://duckdb.org/2021/06/25/querying-parquet.html) - Describes how DuckDB optimizes queries to a Parquet file using projection & filter pushdown.
* [Why Parquet Is the Go-To Format for Data Engineers](https://luminousmen.com/post/why-parquet-is-the-goto-format-for-data-engineers) - A graphical description of the Parquet format with optimization and best practices.
* [Column Storage for the AI Era](https://sympathetic.ink/2025/12/11/Column-Storage-for-the-AI-era.html) - A proposal by the creator of Parquet to better support AI workloads by adding encodings and metadata.
* [I spent 8 hours learning Parquet. Here’s what I discovered](https://vutr.substack.com/p/the-overview-of-parquet-file-format) - A graphical description of the Parquet format.

### Documentation

* [Parquet](https://github.com/apache/parquet-format) ⭐ 2,535 | 🐛 90 | 🌐 Thrift | 📅 2026-08-02 - The specification for Apache Parquet and Apache Thrift definitions to read and write Parquet metadata.
* [Apache Parquet Documentation](https://parquet.apache.org/docs/) - The official documentation for Apache Parquet.

### Educative resources

* [ssphub](https://ssphub.github.io/ssphub-ateliers-parquet/) - Un atelier de l'Insee illustrant l'utilisation des données du recensement 🇫🇷 diffusées au format Parquet.

### Parquet engineering

* [Handling Parquet Files](https://duckdb.org/docs/stable/guides/performance/file_formats#handling-parquet-files) - Recommendations about the row group size and the Parquet file sizes.
* [Les filtres de Bloom dans Parquet](https://www.icem7.fr/outils/les-filtres-de-bloom-dans-parquet/) - Un article de fond sur les filtres de Bloom dans Parquet, utiles pour indexer des colonnes non triées, à forte cardinalité.
* [Paging Through a Parquet File in DuckDB: file\_row\_number or OFFSET?](https://rusty.today/blog/paging-parquet-duckdb-file-row-number-vs-offset/) - In-depth investigation about paging through a Parquet file, with recommendations about row group size.
* [Tips for Writing Parquet Files](https://duckdb.org/docs/stable/data/parquet/tips#tips-for-writing-parquet-files) - Tips for choosing the right parameters when writing Parquet files, such as the row group size and the number of row groups per file.

### Tests

* [parquet-testing](https://github.com/apache/parquet-testing) ⭐ 89 | 🐛 20 | 🌐 Python | 📅 2026-08-12 - Testing Data and Utilities for Apache Parquet.

## Related formats

* [Lance](https://github.com/lancedb/lance) ⭐ 6,938 | 🐛 1,016 | 🌐 Rust | 📅 2026-08-14 - Modern columnar data format for ML and LLMs.
* [Vortex](https://github.com/vortex-data/vortex) ⭐ 3,140 | 🐛 346 | 🌐 Rust | 📅 2026-08-15 - A columnar file format designed for high-performance data processing.
* [F3](https://github.com/future-file-format/F3) ⭐ 760 | 🐛 1 | 🌐 Rust | 📅 2025-11-03 - A data file format that is designed with efficiency, interoperability, and extensibility in mind.
* [Nimble](https://github.com/facebookincubator/nimble) ⭐ 729 | 🐛 152 | 🌐 C++ | 📅 2026-08-07 - File format for storage of large columnar datasets.
* [GeoParquet](https://geoparquet.org/) - Specification for storing geospatial vector data (point, line, polygon) in Parquet.
* [Iceberg](https://iceberg.apache.org/) - A high-performance format for huge analytic tables that supports Parquet as one of its storage formats.
* [ORC](https://orc.apache.org/) - Self-describing type-aware columnar file format designed for Hadoop workloads.

## Contributing

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-15._
