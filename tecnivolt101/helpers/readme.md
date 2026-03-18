Following helpers to be created in HA:

This is the main template responisble for dynamic charging based on solar production and energy prices.
https://github.com/aceindy/klefr6934-mid-faker/blob/main/tecnivolt101/helpers/Technivolt_charge_current_1

And this helper makes use of the following helpers, they are used for fine-tuning:

input_select.charge_car                    Multiline selector allows to choose from a list of available car-batteries

input_number.ev_charge_price_threshold     The EV Charge price is the threshold to decide wether to use solar excess production or charge when the price is below the threshold. [default 0.15€/kWh]

input_number.force_ev_charge_below         Will start charging always when battery level is below this value, after that normal rules apply [default 20%]

input_boolean.manual_charge_override       Will force charging regardless of price/solar production
