<h1 align="center" width="100vw">
  <img alt="Logo: InvoiceGenerator" src="https://github.com/PedroLucasOM/InvoiceGenerator/blob/master/logo.png" />
</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-1.0.0-green.svg?cacheSeconds=2592000" />
  <img src="https://img.shields.io/badge/java-11-green.svg" />
  <img src="https://img.shields.io/badge/spring-2.4.5-green.svg" />
  <a href="https://github.com/PedroLucasOM/InvoiceGenerator#readme" target="_blank">
    <img alt="documentation" src="https://img.shields.io/badge/documentation-yes-green.svg" />
  </a>
  <a href="https://github.com/PedroLucasOM/InvoiceGenerator/graphs/commit-activity" target="_blank">
    <img alt="maintenance" src="https://img.shields.io/badge/maintained-yes-green.svg" />
  </a>
  <a href="https://twitter.com/PedroLucasOM" target="_blank">
    <img alt="Twitter: PedroLucasOM" src="https://img.shields.io/twitter/follow/PedroLucasOM.svg?style=social" />
  </a>
</p>

> :computer: Spring Batch Application to generate invoices based in clients, transactions and credit cards :credit_card:  inside of a configured database with Docker :whale:.


# 1. About the Project

## Implemented Job

It's responsible to execute two steps that will import credit cards and transactions from a .txt file to a configured Datasource. After it, it will gerenate multiples files to each credit card invoice with their respective transactions.


