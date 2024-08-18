# Welcome to Anemos.jl

[![Build Status](https://github.com/thezachdrake/Anemos.jl/actions/workflows/CI.yml/badge.svg?branch=main)](https://github.com/thezachdrake/Anemos.jl/actions/workflows/CI.yml?query=branch%3Amain)

> [!Warning]
> This project is under very early development and should not be used in production systems. Our goal is to get to a stable build as soon as possible.

Anemos.jl is  framework for data pipelines and ETL, inspired heavily be Apache Airflow. The goal is to create a Julian approach to ETL orchestration that can leverage the concurrency and speed of Julia, with the the simplicity and monitoring capabilities of something like Airflow. We intend to use [Geneie.jl](https://github.com/GenieFramework/Genie.jl) to expose API and UI capabilities, a SQLite database for logs with [SQLite.jl](https://github.com/JuliaDatabases/SQLite.jl), and the simplicity of liniear workflows like [Chain.jl](https://github.com/jkrumbiegel/Chain.jl) and [TransformsBase.jl](https://github.com/JuliaML/TransformsBase.jl).
