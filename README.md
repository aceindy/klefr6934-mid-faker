This is the yaml for an ESP32 in combination with a TTL2RS485 in order to 'fake' a KLEFR6934/PRO380 MID energy meter connected to a Technivolt 100 / 101 EV charger using the energy data from Home Assistant.

The StandAlone version is just using the energy data from home-assistant 1:1 without any manilpulation.

The Technivolt101 version is manipulating the energy data to take solar-production and energy prices into consideration.

<img width="1627" height="354" alt="image" src="https://github.com/user-attachments/assets/01d95ec6-6de0-4176-b473-daab01ce6a26" />

PS: Based on https://github.com/keerekeerweere/ESPhome-simulate-eastron-SDM630-DSMR , big thanks!
