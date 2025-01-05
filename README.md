# blueprint_hilo
Blueprint permettant de configurer la température des thermostats selon le statut du sensor defi hilo. L'intégration HACS Hilo avec Home Assistant est requise pour utiliser ce blueprint. (https://github.com/dvd-dev/hilo)

Changement:
2025: Commentaire des sections temperature_scheduled, sinon c'est problematique quand tu as 3 thermopompes qui baisse de chaleur plus de 24h d'avance aussitot que le trigger scheduled arrive.
