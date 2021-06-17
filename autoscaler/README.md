Use ray==1.4.0

```ray up autoscaler.yaml --no-config-cache``` \
To sync local changes after cluster setup, run the command above again. 

### For non-efs version:
use ```autoscaler-raw.yaml``` \
modify line 105 and 151 \
To set the number of workers, modify line 70

### For non-efs-ram version:
use ```autoscaler-raw.yaml``` \
modify line 105 and 154 \
To set the number of workers, modify line 70

### For efs version:
use ```autoscaler-efs-raw.yaml``` \
modify lines 152 and 165 accordingly \
To set the number of workers, modify line 70



