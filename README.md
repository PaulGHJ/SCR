# SCR
Contrastive Learning with Semantic Consistency Constraint

# train
main.py /dataset_dir --k --beta 0.00001 --lambd 0.001 --epochs 100

# test
evaluate.py dataset_dir resnet18.pth --lr-classifier 0.3 --checkpoint-dir ./lincls/ --epochs 100
