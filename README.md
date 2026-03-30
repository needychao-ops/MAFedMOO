| Method              | Key Assumptions                                     |     Convergence Rate     | Communication Cost | Parameter-free |   Momentum   |
| :------------------ | :-------------------------------------------------- | :----------------------: | :----------------: | :------------: | :----------: |
| **FSMGDA**          | Smoothness, Bounded Grad                            | $\mathcal{O}(1/T^{1/4})$ | $\mathcal{O}(Md)$  |    $\times$    |   $\times$   |
| **FedCMOO**         | Smoothness, Bounded Var/Grad, Bounded Heterogeneity | $\mathcal{O}(1/T^{1/4})$ |  $\mathcal{O}(d)$  |    $\times$    |   $\times$   |
| **MAFedMOO (Ours)** | Smoothness, Bounded Var/Grad,                       | $\mathcal{O}(1/T^{1/4})$ | $\mathcal{O}(Md)$  |  $\checkmark$  | $\checkmark$ |
