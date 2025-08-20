# pgEdge Announces Launch of pgEdge Platform v25

pgEdge, Inc., the leading company dedicated to distributed Postgres, today announced the availability of pgEdge Platform v25, iterating on their industry-leading Platform v24 releases. With this latest release pgEdge rolls out a number of significant improvements that bolster its position as the only distributed Postgres solution that is open (source available) and completely based on the standard PostgreSQL database.

 pgEdge Platform v25 builds upon Platform v24 advancements in Postgres logical replication that include large object support as well as enhanced error handling. pgEdge continues to be a viable open source distributed PostgreSQL alternative for legacy database workloads requiring multi-master capability.

 Platform v25 introduces a variety of robust new features, including:

 * True Zero Downtime for Node Addition and PostgreSQL Upgrades: pgEdge customers now have the ability to add a new node with true zero write downtime. This equates to zero downtime for not only node additions but also now supports Postgres version upgrades:

 * A user’s cluster is Always-On, Write-Anywhere. All nodes are fully read and write-enabled at all times, while bringing a new node up to speed and adding it to the cluster to accept traffic. Major (and even minor) version upgrades can now be performed as rolling updates by adding a new, upgraded node and then decommissioning the old node, instead of taking the node offline, upgrading it, and working to reattach it. pgEdge continues to enhance this zero downtime capability.

 * Expanded Automatic Conflict Resolution: Conflict resolution now handles a broader range of scenarios automatically, including common edge cases encountered in distributed workloads.:

 * Insert-RowExists scenarios, for example two Inserts with the same Primary Key, now automatically converts the second insert into an all-column update Delete-RowMissing scenarios, for example attempting to delete a non-existent row, are automatically resolved as desired behaviour It is now possible to configure pgEdge to also check for non-null Unique Constraint violations, and attempt to resolve with a Last-Write-Wins update

 * Improved Performance: Exception Handling and Lag Monitoring have both been overhauled for greater performance and accuracy.

 * Exception Handling can now be performed in-memory, providing an order-of-magnitude speed improvement over the original pgLogical method.  Lag tracking is now calculated at the target node, meaning an improved accuracy, as well as preventing an ever-increasing reported lag during times when there is no write activity to replicate

 * Interactive Installation: A new installation will interactively guide customers through the needed information and create the configuration file for them. This provides a much easier way for customers to set up their cluster, especially for first time users, that ensures configuration files are created properly. The new script also makes sure that users know what information is needed for a successful install.

 * Backup & Restore Strategy / pgBackrest Integration: pgBackrest is included as a default part of the Platform configuration, allowing users to easily configure backups. Additionally, a backup & restore Strategy Guide is also included to get customers started. This means that there is now a provided component to allow users to configure backup and restore without having to find and install their own backup method. There is also provided guidance on recommended backup/restore strategies.
* ACE (Active Consistency Engine) Enhancements: This release delivers substantial improvements to ACE, pgEdge’s powerful tool for validating and repairing data consistency. These enhancements bring faster performance, improved flexibility, and expanded automation for detecting and resolving data discrepancies across nodes, especially in large-scale datasets.

 “We are very pleased to announce that pgEdge Platform v25 is available and as before, built on standard open source PostgreSQL,” said Phillip Merrick, Co-founder and CEO of pgEdge. “In collaboration with our customers, partners and community, we have designed these new features to make the product easier to use while continuing to enhance our distributed Postgres capabilities in further support of high availability and low latency.”

 The new pgEdge Platform v25 is available now for a free download here: https://www.pgedge.com/get-started/platform

 About pgEdge pgEdge, the leading company dedicated to distributed Postgres, is on a mission to make it easy for developers to build and deploy highly distributed database applications across global networks. Founded by industry veterans with decades of PostgreSQL expertise, pgEdge is headquartered in Northern Virginia. Its customers include prominent enterprises such as Bertelsmann, Qube RT, Jobot, European Parliament, and several U.S. government agencies. pgEdge’s investors include Akamai Technologies, Inc., Qube Research & Technology (QRT), Rally Ventures, Sands Capital Ventures, Grotech Ventures, and Sand Hill East.

 For more information, visit www.pgedge.com.

 The post pgEdge Announces Launch of pgEdge Platform v25 appeared first on citybiz. 

---

[Original/Source Press Release](https://www.citybiz.co/article/733829/pgedge-announces-launch-of-pgedge-platform-v25/)
                    

[Newsramp.com TLDR](https://newsramp.com/curated-news/pgedge-platform-v25-launches-with-zero-downtime-upgrades-enhanced-distributed-postgres/f2a32e0d414b8e2a9bd02a6d383d5fef) 

 



[Reddit Post](https://www.reddit.com/r/Business_NewsRamp/comments/1mvemgx/pgedge_platform_v25_launches_with_zero_downtime/) 



![Blockchain Registration](https://cdn.newsramp.app/citybiz/qrcode/258/20/filoaaBb.webp)