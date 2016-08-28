# BlinkyAle

To start your Nerves app:

  * Install dependencies with `mix deps.get`
  * Create firmware with `mix firmware`
  * Burn to an SD card with `mix firmware.burn`

## Learn more

  * Official docs: https://hexdocs.pm/nerves/getting-started.html
  * Official website: http://www.nerves-project.org/
  * Discussion Slack elixir-lang #nerves ([Invite](https://elixir-slackin.herokuapp.com/))
  * Source: https://github.com/nerves-project/nerves


## Running Blinky on the LinkIt Smart Duo

You will need to prepare your LinkIt Smart to run Nerves By following the instrutions
on the system repository found at https://github.com/nerves-project/nerves_system_linkit

Connect an LED with resistor to the P1 and Ground Pins on the LinkIt Smart Duo.
Burn and run, Once Elixir boots you should have a blinking LED.
