# ce7412-project
MLP
```
python mlp.py
```
Node2vec
```
python mlp.py --use_node_embedding
```
GCN
```
python gnn.py
```
GraphSage
```
python gnn.py --use_sage
```
DeepGCN/ResGCN/ResGCN+
```
cd DeepGCN
python main.py --use_gpu --conv_encode_edge --use_one_hot_encoding --num_layers 28 --gcn_aggr mean --epochs 100
python main.py --use_gpu --conv_encode_edge --use_one_hot_encoding --num_layers 28 --block res --gcn_aggr mean --epochs 100
python main.py --use_gpu --conv_encode_edge --use_one_hot_encoding --num_layers 28 --block res+ --gcn_aggr mean --epochs 100
```
