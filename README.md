# Rust K-MEANS

- An unsupervised learning algorithm (k-means) implementation to differentiate cat breeds example (Persian, British short hair, Ragdoll).

# Run

- install rust
- install gnu-plot
- update configuration for generation and correct answers in generate.toml
- cargo run --bin generate -- --config-file config/generate.toml > training.csv (generate sample training data from config)
- cat training.csv | cargo run --bin cluster > results.csv (pass sample data to run the clustering and return results in csv)
- cat results.csv | cargo run --bin plot (visualize your result)
- in graph .. (Red = persian, Green = British short hair, Blue = Ragdoll)
