Le tableau suivant présente les types de passerelle et le débit total estimé par référence de passerelle. Cette table s’applique aux modèles de déploiement classique et Resource Manager. 

La tarification varie en fonction des différentes références de passerelle. Pour plus d’informations, consultez [Passerelle VPN Tarification](https://azure.microsoft.com/pricing/details/vpn-gateway).

Notez que la référence de la passerelle UltraPerformance n’est pas représentée dans cette table. Pour plus d’informations sur la référence UltraPerformance, consultez la documentation [ExpressRoute](../articles/expressroute/expressroute-about-virtual-network-gateways.md).

|  | **Débit de passerelle VPN (1)** | **Tunnels IPsec max de passerelle VPN (2)** | **Débit de passerelle ExpressRoute** | **Passerelle VPN et ExpressRoute coexistants** |
| --- | --- | --- | --- | --- |
| **Référence de base (3)(5)(6)** |100 Mbits/s |10 |500 Mbits/s (6) |Non |
| **Référence SKU Standard (4) (5)** |100 Mbits/s |10 |1 000 Mbits/s |Oui |
| **Référence SKU Hautes performances (4)** |200 Mbits/s |30 |2 000 Mbits/s |Oui |


(1) Le débit de la passerelle VPN est une estimation calculée à partir de mesures entre réseaux virtuels dans la même région Azure. Ce débit n’est pas garanti pour les connexions intersites via Internet. Il s’agit de la mesure du débit maximal possible.

(2) Le nombre de tunnels fait référence aux VPN basés sur un itinéraire. Un VPN basé sur des stratégies peut uniquement prendre en charge un seul tunnel VPN de site à site.

(3) Le protocole BGP n’est pas pris en charge pour la référence SKU De base.

(4) Les VPN basés sur des stratégies ne sont pas pris en charge pour cette référence SKU. Ils sont uniquement pris en charge sur la référence SKU De base.

(5) Les connexions VPN S2S en mode actif-actif avec des passerelles ne sont pas prises en charge pour cette référence SKU. Le mode actif/actif est uniquement pris en charge sur la référence SKU HighPerformance.

(6) La référence SKU de base est déconseillée pour une utilisation avec Expressroute.
