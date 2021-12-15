#### Validations:
| Name                               | Req/Opt  | Type   | Range 	 | Description                                                                    |
|------------------------------------|:---------|:-------|:----------|:-------------------------------------------------------------------------------|
| FriendlyName                       | Required | string |           | Non-empty string. Unique in the collection. Case insensitive comparison        |
| Url                                | Required | string |           | Non-empty unique string. Unique in the collection. Case insensitive comparison |
| BeamInSoundVolumeSelect            | Required |  int   |    0-3    |                                                                                |
| ClampMaxP2P                        | Required |  int   |  700-4000 |                                                                                |
| EnableScreensaverAnimation         | Required | string |           | Can be one of the following options: "Auto", "On" or "Off"                     |
| IgnoreEkoStethoscopeId             | Required |  bool  |           |                                                                                |
| MinimizeWhenIdle                   | Required |  bool  |           |                                                                                |
| SecondScreenHomeButton             | Required |  bool  |           |                                                                                |
| SelectedStethoscope                | Required | string |           | Can be one of the [SelectedStethoscope Options](#ref.SelectedStethoscope)                                 |
| ShowCloseButton                    | Required |  bool  |           |                                                                                |
| ShowMinimizeButton                 | Required |  bool  |           |                                                                                |
| ShowPrivacyModeOption              | Required | string |           | Can be one of the following options: "Auto", "On" or "Off"                     |
| TVSwitcherInSessionHDMI            | Required |  int   |    1-4    |                                                                                |
| TVSwitcherOutOfSessionHDMI         | Required |  int   |    1-4    |                                                                                |
| TVSwitcherOutOfSessionUseTVDefault | Required |  bool  |           |                                                                                |

#### SelectedStethoscope Options:
- PCPStethoscopeUSB
- PCPStethoscopeTethered
- LittmannStethoscope
- EkoStethoscope
- None
