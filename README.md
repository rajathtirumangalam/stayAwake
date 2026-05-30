# StayAwake (NVDA Add-on)

StayAwake is a lightweight NVDA add-on that prevents Windows from automatically sleeping, locking, or entering an idle state while it is enabled.

Instead of generating artificial mouse movements or keyboard activity, StayAwake uses supported Windows APIs to safely signal that the system should remain active.

This makes it useful during presentations, meetings, long-running tasks, downloads, remote sessions, media playback, and other situations where automatic sleep or lock behavior would be disruptive.

## Features

* Prevents automatic system sleep while enabled
* Prevents automatic idle lock while enabled
* Toggle StayAwake on or off with a keyboard shortcut
* Announce the current StayAwake status at any time
* Uses supported Windows APIs rather than simulated input
* Automatically restores normal system behavior when disabled
* Automatically releases the wake request when NVDA exits
* Lightweight and efficient

## Default Keyboard Shortcuts

* **NVDA + Ctrl + Shift + I**
  Toggle StayAwake on or off

* **NVDA + Ctrl + Shift + A**
  Announce whether StayAwake is currently enabled

All shortcuts can be customized through:

NVDA Menu → Preferences → Input Gestures → StayAwake

## Common Use Cases

StayAwake can be useful when:

* Delivering presentations or training sessions
* Participating in lengthy online meetings
* Monitoring long-running processes
* Downloading or transferring large files
* Reading lengthy documents without interruption
* Preventing unwanted screen locks during demonstrations
* Running accessibility testing sessions

## How It Works

When enabled, StayAwake requests that Windows keep the system active by using supported operating system APIs.

It does not:

* Simulate mouse movement
* Generate fake keyboard input
* Modify Windows power plans
* Permanently change system settings

When StayAwake is disabled, Windows immediately returns to its normal power-management behavior.

## Notes

* StayAwake only prevents automatic sleep and idle lock events.
* Users can still manually lock the computer or put the system to sleep.
* Actual behavior may vary depending on organizational policies, domain restrictions, or manufacturer-specific power management software.
* StayAwake does not override administrator-enforced security policies.

## About the Author

Rajath Tirumangalam is an accessibility professional, speaker, developer, and author focused on digital accessibility, assistive technology, and inclusive design.

Author of *The Invisible User: What Your Code Assumes*.

Website: https://www.rajathtirumangalam.com

GitHub: https://github.com/rajathtirumangalam

## License

MIT License
