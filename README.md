# SCR
Contrastive Learning with Semantic Consistency Constraint

# train
main.py /dataset_dir --k 20 --beta 0.00001 --lambd 0.001 --epochs 200

# test
evaluate.py dataset_dir resnet18.pth --lr-classifier 0.3 --checkpoint-dir ./lincls/ --epochs 100
