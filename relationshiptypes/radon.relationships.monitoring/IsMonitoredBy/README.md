## Monitoring IsMonitoredBy relashionship

Monitoring-specific relationship type representing Cloud Service-to-PushaGateway communication

| Name            | URI                                            | Version | Derived From                     |
| :-------------- | :--------------------------------------------- | :------ | :------------------------------- |
| `IsMonitoredBy` | `radon.relationships.monitoring.IsMonitoredBy` | 1.0.0   | `tosca.relationships.ConnectsTo` |

### Inputs

| Name                 | Required | Type     | Constraint | Default Value | Description                       |
| :------------------- | :------- | :------- | :--------- | :------------ | :-------------------------------- |
| `monitored_function` | `true`   | `string` |            |               | Function for the generated graphs |
| `user_email`         | `true`   | `string` |            |               | User Email to Grafana             |
| `grafana_ip`         | `true`   | `string` |            |               | Grafana ip                        |
