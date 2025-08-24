# connectome-based-drosophila-AI-model
초파리 커넥톰의 후각계통 회로를 인공신경망으로 구현하고 DoOR데이터베이스를 기반으로 냄새자극의 분류(classification) 성능을 측정하고, 일반인공신경망의 성능과 비교하여, 초파리 후각 시스템의 생태학적 특성을 이해한다.

🎯 Goals

1. Develop connectome-based ANN for the Drosophila olfactory system “ADOnet (Artificial Drosophila Olfactory network)”
    1. design the architecture only with the feedforward network (no LN, no feedback synapses)
        1. using FC layers
        2. using graph neural networks (GNNs) 
    2. test the classification performance for DoOR database
        1. compare it with that of general ANNs of the similar size in terms of the number of parameters
    3. expand the model to incorporate lateral/feedback signaling
    4. present the result in KOSOMBE (의용생체공학회) 2025 Fall (November)

