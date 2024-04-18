
Some mathematical experiments with Riemannian Geometric perspective of Relative Entanglement Entropy which is closely related with Kulbeck-Leibler Divergence in Information Theory. In fact local correspondence between  KL-Divergence and Fisher-Rao metric may be closely related with the last formula derived here.

$$S(\rho_{\lambda} || \rho_{\lambda+\delta \lambda}) = Tr[\rho_{\lambda} \ ln(\frac{\rho_{\lambda}}{\rho_{\lambda+\delta \lambda}})]$$
$$ln(\rho_{\lambda+\delta \lambda}) = ln(\rho_{\lambda}+\delta \lambda_{i} \ \partial^i \rho_{\lambda} + \frac{1}{2}\delta \lambda_{i} \delta \lambda_{j} \ \partial^i \partial^j \rho_{\lambda} + \mathcal{O}(\delta\lambda^{2+})) \approx ln(\rho +\delta \lambda_{i} \ \partial^i \rho + \frac{1}{2}\delta \lambda_{i} \delta \lambda_{j} \ \partial^i \partial^j \rho) =ln(\rho + g ) = ln(\rho)+\rho^{-1} g - \frac{1}{2}\rho^{-2}g^2+\mathcal{O}(g^{2+})$$
$$\text{where: } \ g = \delta \lambda_{i} \ \partial^i \rho + \frac{1}{2}\delta \lambda_{i} \delta \lambda_{j} \ \partial^i \partial^j \rho \ , \  \ \ \ \text{so that upto $\mathcal{O}(\delta \lambda^2)$} \ :   \ g^2 \approx (\delta \lambda_{i} \ \partial^i \rho )^2$$$$S(\rho_{\lambda} || \rho_{\lambda+\delta \lambda}) \approx Tr[ \ \rho \ ( \ ln \rho  \ - ln\rho -\rho^{-1} ( \ \delta \lambda_{i} \ \partial^i \rho + \frac{1}{2}\delta \lambda_{i} \delta \lambda_{j} \ \partial^i \partial^j \rho \ ) + \frac{1}{2}\rho^{-2} \ (\delta \lambda_{i} \ \partial^i \rho )^2 \ ) \ ]  $$
$$ = Tr[ \ -  \ \delta \lambda_{i} \ \partial^i \rho - \frac{1}{2} \  \ \delta \lambda_{i} \delta \lambda_{j} \ \partial^i \partial^j \rho \  + \frac{1}{2}\rho^{-1} \ (\delta \lambda_{i} \ \partial^i \rho )^2 \ ) \ ]=Tr[ \ - \  \frac{1}{2} \  \ \delta \lambda_{i} \delta \lambda_{j} \ \partial^i \partial^j \rho \  + \frac{1}{2}\rho^{-1} \ (\delta \lambda_{i} \ \partial^i \rho )^2 \  \ ] $$

$$=\frac{1}{2} \ Tr[ \  \rho^{-1}  \delta \lambda_{i} \delta \lambda_{j} \ \partial^i \rho \  \partial^j \rho  \ - \  \delta \lambda_{i} \delta \lambda_{j} \ \partial^i \partial^j \rho \ \ ] =\frac{1}{2} \ Tr[ \   \rho^{-1} \ \ \partial^i \rho \  \partial^j \rho  \ - \  \partial^i \partial^j \rho \ \ ] \ \delta \lambda_{i} \delta \lambda_{j} \  $$
$$ = - \frac{1}{2} \ Tr[ \  \rho \  \partial^i \partial^j \  ln (\rho) \  \ ] \ \delta \lambda_{i} \delta \lambda_{j} \ $$

SO that we have : 

 $$When \ : \ \  \ \delta \lambda \to 0, \ \text{at the leading $\mathcal{O}(\delta \lambda^2) \ :$} \ \ \ \ S(\rho_{\lambda} || \rho_{\lambda+\delta \lambda}) = g_{ij} \ \delta \lambda_{i} \delta \lambda_{j} \ \  $$

$$\text{where: } \ \ g_{ij} = - \frac{1}{2} \ Tr[ \  \rho \  \partial^i \partial^j \  ln (\rho) \  \ ] = \frac{1}{2} \ Tr[ \   \rho^{-1} \ \ \partial^i \rho \  \partial^j \rho  \ - \  \partial^i \partial^j \rho \ \ ] $$
 