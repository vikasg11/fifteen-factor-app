### X.	Dev/Prod Parity

Keep Development, Staging, and Production as Similar as Possible

The twelve-factor app is designed for continuous deployment by keeping the gap between development and production small. The twelve-factor also resist using different backing services between development and production, even when adapters theoretically abstract away any differences in backing services. Backing services, such as the app’s database, queueing system, or cache, is one area where dev/prod parity is important. 

Additionally, having the right processes like Continuous Integration (CI) and Continuous Delivery (CD) in place facilitates bridging this gap further.

