# Lab 7 Training Twitter Sentiment Analysis

### Training values and outcome graphs

| activiation function | embedding_dim | num_layers | hidden_dim | dropout | bidirectional | epochs | sequence length | batch_size | Adam | image |
| -- | ------------- | ---------- | ---------- | ------- | ------------- | ------ | --------------- | ---------- | ----- | - |
| TanH | 100 | 3 | 124 | 0.5 | True | 8 | 16 | 10 | 3e-4 | ![](graphs/batch10.png) |
| TanH | 100 | 3 | 124 | 0.5 | True | 8 | 16 | 20 | 3e-4 | ![](graphs/batch20.png) |
| TanH | 100 | 3 | 124 | 0.5 | True | 8 | 16 | 40 | 3e-4 | ![](graphs/batch40.png) |
| TanH | 100 | 3 | 124 | 0.5 | True | 8 | 16 | 80 | 3e-4 | ![](graphs/batch80.png) |
| TanH | 100 | 3 | 124 | 0.5 | True | 8 | 16 | 160 | 3e-4 | ![](graphs/batch160.png) |
| TanH | 100 | 3 | 124 | 0.5 | True | 8 | 16 | 320 | 3e-4 | ![](graphs/batch320.png) |
| TanH | 100 | 3 | 124 | 0.5 | True | 8 | 16 | 640 | 3e-4 | ![](graphs/batch640.png) |
| TanH | 100 | 3 | 124 | 0.5 | True | 8 | 16 | 1000 | 3e-4 | ![](graphs/batch1000.png) |
| TanH | 100 | 3 | 124 | 0.5 | True | 8 | 16 | 1280 | 3e-4 | ![](graphs/batch1280.png) |
| TanH | 100 | 3 | 124 | 0.5 | True | 8 | 16 | 2000 | 3e-4 | ![](graphs/batch2000.png) |
| TanH | 100 | 3 | 124 | 0.5 | True | 8 | 16 | 2560 | 3e-4 | ![](graphs/batch2560.png) |
| TanH | 100 | 3 | 124 | 0.5 | True | 8 | 16 | 2560 | 3e-4 | ![](graphs/batch2560.png) |
| TanH | 100 | 3 | 124 | 0.5 | True | 8 | 16 | 2560 | 3e-4 | ![](graphs/batch2560.png) |
| TanH | 100 | 3 | 124 | 0.5 | True | 8 | 16 | 2560 | 3e-4 | ![](graphs/batch2560.png) |
| TanH | 100 | 3 | 124 | 0.5 | True | 8 | 16 | 2560 | 3e-4 | ![](graphs/batch2560.png) |
| TanH | 100 | 3 | 124 | 0.5 | True | 8 | 16 | 2560 | 3e-4 | ![](graphs/batch2560.png) |
| TanH | 100 | 3 | 256 | 0.5 | True | 20 | 16 | 2560 | 3e-4 | ![](graphs/epoch20.png) |
| TanH | 100 | 3 | 256 | 0.5 | True | 40 | 16 | 2560 | 3e-4 | ![](graphs/epoch40.png) |
| TanH | 100 | 3 | 256 | 0.5 | True | 40 | 16 | 2560 | 3e-4 | ![](graphs/seq2.png) |
| TanH | 100 | 3 | 256 | 0.5 | True | 40 | 16 | 2560 | 3e-4 | ![](graphs/seq4.png) |
| TanH | 100 | 3 | 256 | 0.5 | True | 40 | 16 | 2560 | 3e-4 | ![](graphs/seq8.png) |
| TanH | 100 | 3 | 256 | 0.5 | True | 40 | 16 | 2560 | 3e-4 | ![](graphs/seq16.png) |
| TanH | 100 | 3 | 256 | 0.5 | True | 40 | 16 | 2560 | 3e-4 | ![](graphs/seq24.png) |
| TanH | 100 | 3 | 256 | 0.5 | True | 40 | 16 | 2560 | 3e-4 | ![](graphs/seq32.png) |
| TanH | 100 | 3 | 256 | 0.5 | True | 40 | 24 | 2560 | 1e-4 | ![](graphs/2Adam1e-4.png) |
| TanH | 100 | 3 | 256 | 0.5 | True | 40 | 24 | 2560 | 2e-4 | ![](graphs/2Adam2e-4.png) |
| TanH | 100 | 3 | 256 | 0.5 | True | 40 | 24 | 2560 | 5e-4 | ![](graphs/2Adam5e-4.png) |
| TanH | 100 | 3 | 256 | 0.5 | True | 40 | 24 | 2560 | 9e-4 | ![](graphs/2Adam9e-4.png) |
| TanH | 100 | 3 | 256 | 0.5 | True | 40 | 24 | 2560 | 9e-4 | ![](graphs/2Adam9e-4.png) |
| sigmoid | 100 | 3 | 256 | 0.5 | True | 40 | 24 | 2560 | 9e-4 | ![](graphs/sigmoid.png) |
| ReLU | 100 | 3 | 256 | 0.5 | True | 40 | 24 | 2560 | 9e-4 | ![](graphs/ReLU23.png) |
| ReLU | 100 | 3 | 124 | 0.5 | True | 40 | 24 | 2560 | 9e-4 | ![](graphs/ReLU7382.png) |