# Sliders

The Sliders are code samples ready to be used by any developer aiming to create a custom field to deploy into [Liferay Forms](https://learn.liferay.com/dxp/latest/en/process-automation/forms/introduction-to-forms.html). These samples are based on the [HTML input range](https://www.w3schools.com/tags/att_input_type_range.asp) and are also the ideal starting point to build a new custom field. Right now, there are 2 samples:

|**Name**|**Front-End Framework**|**Liferay Portal Compatibility**|
|--|--|--|
| slider-metaljs | [MetalJS](http://metaljs.com/) | 7.2, 7.3, 7.4 |
| slider-react | [React](https://reactjs.org/) | 7.3, 7.4 |

The Liferay Portal version in which the code samples will be deployed must be set in the `devDependencies` of the `package.json` like:

```
// Dependency compatible with 7.2

  "devDependencies": {
    "@liferay/portal-7.2": "*"
  },
```

```
// Dependency compatible with 7.3

  "devDependencies": {
    "@liferay/portal-7.3": "*"
  },
```

```
// Dependency compatible with 7.4

  "devDependencies": {
    "@liferay/portal-7.4": "*"
  },
```
More details about the dependencies above can be seen on [liferay-cli target platform](https://github.com/liferay/liferay-frontend-projects/blob/master/projects/js-toolkit/docs/manuals/liferay-cli.md#target-platform).
