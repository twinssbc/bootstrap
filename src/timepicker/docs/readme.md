A lightweight & configurable timepicker directive.

### Settings ###

All settings can be provided as attributes in the `<timepicker>` or globally configured through the `timepickerConfig`.

 * `ng-model` <i class="glyphicon glyphicon-eye-open"></i>
 	:
 	The Date object that provides the time state.

 * `hour-step` <i class="glyphicon glyphicon-eye-open"></i>
 	_(Defaults: 1)_ :
 	 Number of hours to increase or decrease when using a button.

 * `minute-step` <i class="glyphicon glyphicon-eye-open"></i>
 	_(Defaults: 1)_ :
 	 Number of minutes to increase or decrease when using a button.

 * `show-meridian` <i class="glyphicon glyphicon-eye-open"></i>
 	_(Defaults: true)_ :
 	Whether to display 12H or 24H mode.

 * `meridians`
 	_(Defaults: null)_ :
 	 Meridian labels based on locale. To override you must supply an array like ['AM', 'PM'].

 * `readonly-input`
 	_(Defaults: false)_ :
 	 Whether user can type inside the hours & minutes input.

 * `mousewheel`
 	_(Defaults: true)_ :
 	 Whether user can scroll inside the hours & minutes input to increase or decrease it's values.


### Popup Settings ###

Options for timepicker can be passed as JSON using the `timepicker-options` attribute.
Specific settings for the `timepicker-popup`, that can globally configured through the `timepickerPopupConfig`, are:

 * `show-meridian`
 	_(Default: true)_ :
 	Whether to display 12H or 24H mode.

 * `timepicker-append-to-body`
  _(Default: false)_:
  Append the timepicker popup element to `body`, rather than inserting after `timepicker-popup`. For global configuration, use `timepickerPopupConfig.appendToBody`.

