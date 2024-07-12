# Comment renvoyer une transaction Bitcoin ayant échoué

Lorsque les utilisateurs envoient des transactions Bitcoin avec des frais très bas, ces transactions sont susceptibles de rester en attente pendant une courte période, puis d'être rejetées par le réseau comme si elles n'avaient jamais eu lieu.

Si les utilisateurs rencontrent une transaction avec un statut d'échec (rejeté) dans Deus, il est recommandé de revérifier son statut à l'aide d'un explorateur de blocs public comme [btc.com](https://btc.com) en recherchant l'ID de transaction. .

Si Deus affiche une transaction comme ayant échoué mais qu'un explorateur de blocs public la montre comme en attente ou confirmée, le problème réside probablement dans Deus. Dans ce cas, les utilisateurs ne doivent pas tenter de renvoyer la transaction pour éviter une double dépense. Au lieu de cela, ils doivent signaler le problème au support du portefeuille Deus pour le dépannage.

Une transaction ne doit être considérée comme ayant échoué que si Deus et l'explorateur de blocs public l'indiquent comme ayant échoué ou rejeté.