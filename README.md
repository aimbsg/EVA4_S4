Model summary :
Requirement already satisfied: torchsummary in /usr/local/lib/python3.6/dist-packages (1.5.1)
----------------------------------------------------------------
        Layer (type)               Output Shape         Param #
================================================================
            Conv2d-1            [-1, 8, 28, 28]              80
            Conv2d-2            [-1, 8, 28, 28]             584
         MaxPool2d-3            [-1, 8, 14, 14]               0
            Conv2d-4           [-1, 16, 14, 14]           1,168
            Conv2d-5           [-1, 16, 14, 14]           2,320
         MaxPool2d-6             [-1, 16, 7, 7]               0
            Conv2d-7             [-1, 32, 5, 5]           4,640
            Conv2d-8             [-1, 32, 3, 3]           9,248
            Conv2d-9             [-1, 10, 1, 1]           2,890
================================================================
Total params: 20,930
Trainable params: 20,930
Non-trainable params: 0
----------------------------------------------------------------
Input size (MB): 0.00
Forward/backward pass size (MB): 0.17
Params size (MB): 0.08
Estimated Total Size (MB): 0.25
----------------------------------------------------------------
/usr/local/lib/python3.6/dist-packages/ipykernel_launcher.py:20: UserWarning: Implicit dimension choice for log_softmax has been deprecated. Change the call to include dim=X as an argument.


------------------------------------------------------------------------------------------------------------

Model log : 
 0%|          | 0/469 [00:00<?, ?it/s]/usr/local/lib/python3.6/dist-packages/ipykernel_launcher.py:20: UserWarning: Implicit dimension choice for log_softmax has been deprecated. Change the call to include dim=X as an argument.
loss=0.22082464396953583 batch_id=468: 100%|██████████| 469/469 [00:11<00:00, 44.66it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.1085, Accuracy: 9671/10000 (97%)

loss=0.12394396215677261 batch_id=468: 100%|██████████| 469/469 [00:11<00:00, 41.72it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0763, Accuracy: 9764/10000 (98%)

loss=0.17745094001293182 batch_id=468: 100%|██████████| 469/469 [00:11<00:00, 41.88it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0499, Accuracy: 9847/10000 (98%)

loss=0.018580934032797813 batch_id=468: 100%|██████████| 469/469 [00:11<00:00, 40.79it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0425, Accuracy: 9856/10000 (99%)

loss=0.042125552892684937 batch_id=468: 100%|██████████| 469/469 [00:11<00:00, 42.49it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0411, Accuracy: 9868/10000 (99%)

loss=0.024758944287896156 batch_id=468: 100%|██████████| 469/469 [00:11<00:00, 42.60it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0411, Accuracy: 9867/10000 (99%)

loss=0.004694963339716196 batch_id=468: 100%|██████████| 469/469 [00:10<00:00, 42.99it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0364, Accuracy: 9885/10000 (99%)

loss=0.02935701049864292 batch_id=468: 100%|██████████| 469/469 [00:10<00:00, 43.32it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0440, Accuracy: 9867/10000 (99%)

loss=0.029616674408316612 batch_id=468: 100%|██████████| 469/469 [00:10<00:00, 42.95it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0392, Accuracy: 9889/10000 (99%)

loss=0.00252455472946167 batch_id=468: 100%|██████████| 469/469 [00:11<00:00, 42.07it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0356, Accuracy: 9888/10000 (99%)

loss=0.022372132167220116 batch_id=468: 100%|██████████| 469/469 [00:10<00:00, 41.88it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0316, Accuracy: 9901/10000 (99%)

loss=0.03953751549124718 batch_id=468: 100%|██████████| 469/469 [00:10<00:00, 43.09it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0382, Accuracy: 9894/10000 (99%)

loss=0.0020439624786376953 batch_id=468: 100%|██████████| 469/469 [00:10<00:00, 43.33it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0388, Accuracy: 9884/10000 (99%)

loss=0.0008528828620910645 batch_id=468: 100%|██████████| 469/469 [00:10<00:00, 43.67it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0335, Accuracy: 9900/10000 (99%)

loss=0.024084359407424927 batch_id=468: 100%|██████████| 469/469 [00:10<00:00, 42.93it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0361, Accuracy: 9893/10000 (99%)

loss=0.126439169049263 batch_id=468: 100%|██████████| 469/469 [00:11<00:00, 42.27it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0392, Accuracy: 9898/10000 (99%)

loss=0.004056950565427542 batch_id=468: 100%|██████████| 469/469 [00:10<00:00, 44.68it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0397, Accuracy: 9907/10000 (99%)

loss=0.0002117455005645752 batch_id=468: 100%|██████████| 469/469 [00:10<00:00, 44.36it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0405, Accuracy: 9889/10000 (99%)

loss=0.005338072776794434 batch_id=468: 100%|██████████| 469/469 [00:10<00:00, 43.98it/s]

Test set: Average loss: 0.0437, Accuracy: 9898/10000 (99%)
