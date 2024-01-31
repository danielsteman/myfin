# myfin

Collect financial transactions of individuals, draw conclusions from these transactions and in return provide insights. For instance, many individuals have a busy life and don't think about optimizing their financial situation. The ones that do are usually using a self managed Excel sheet to gain insight. If individuals can get the right information in an efficient way (without spending too much time), they might make financial decisions that can impact their financial situation in the long run in a positive way. Potential benefits of an analysis on its financial transactions for an individual are:

- Detect overspending on a particular product or service that is bought periodically, such that actions can be taken to prevent this, resulting in reduced costs.
- How to best allocate surplus income to build up wealth on a certain horizon. This shows the effect of compounding interest of various savings accounts. Or the expected (risk-weighted) return on an ETF portfolio. This way, an individual can take opportunity costs into account with making short term financial decisions (spending rather than saving).

## Other apps

## Components

### Parser

A parser to process transactions data from different sources, transform them into workable data and write this data to a database.

### Pre-processor

A pre-processor that takes parsed data and transforms it into a dataset that can be used to train a classification model.

### Data ingestion interface

An interface that makes it possible to submit data.

### Data insights interface

An interface through which insights about data are shared.

### User management

Authentication and authorization.
