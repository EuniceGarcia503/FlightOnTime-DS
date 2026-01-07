# 📂 Datos originales.
⚠️ **Los archivos contenidos en esta carpeta corresponden a los datos originales del proveedor y no deben ser modificados.**

Cualquier transformación o ingeniería de variables se realiza en carpetas posteriores del pipeline.

---

🏛️**Fuente de los datos:** 

**Organismo:**


Bureau of Transportation Statistics (BTS)

Oficina de Estadísticas de Transporte del Departamento de Transporte de EE. UU.

**Dependencia:**


U.S. Department of Transportation (DOT)

Departamento de Transporte de EE.UU.

**Portal oficial:**

[BTS TranStats](https://www.transtats.bts.gov/DL_SelectFields.aspx?gnoyr_VQ=FGJ&QO_fu146_anzr=b0-gvzr)


**Dataset:**


*On-Time Performance – Domestic Flights*

**Fuente alternativa de acceso:**


[Kaggle](https://www.kaggle.com/datasets/hrishitpatil/flight-data-2024?resource=download) (mirror del dataset original de BTS)



     
**Variables principales:**

**0.  year** (Año calendario del vuelo)
**1. month** (Mes del año calendario del vuelo)
**2. day_of_month** (Día del mes calendario del vuelo)
**3. day_of_week** (Día de la semana calendario del vuelo)
**4. fl_date** (Fecha completa del vuelo)
**5. op_unique_carrier** (Código de aerolínea operadora del vuelo)
**6. op_carrier_fl_num** (número de vuelo asignado por aerolínea)
**7. origin** (Código del aeropuerto de origen del vuelo)
**8. origin_city_name** (Ciudad del aeropuerto de origen)
**9. origin_state_nm** (Estado/Provincia del aeropuerto de origen.)
**10. dest** (Código del aeropuerto de destino)
**11. dest_city_name** (Ciudad del aeropuerto destino)
**12. dest_state_nm** (Estado/Provincia del aeropuerto destino)
**13. crs_dep_time** (Hora programada de salida del vuelo)
**14. dep_time** (Hora real de salida del vuelo)
**15. dep_delay** (Minutos de retraso en la salida del vuelo)
**16. taxi_out** (Tiempo de rodaje antes del despegue del avión)
**17. wheels_off** (Momento en el que el avión despega)
**18. wheels_on** (Momento de aterrizaje del avión)
**19. taxi_in** (Tiempo de rodaje después del aterrizaje del avión)
**20. crs_arr_time** (Hora programada de llegada del vuelo)
**21. arr_time** (Hora real de llegada del vuelo)
**22. arr_delay** (Minutos de retraso en llegada del vuelo)
**23. cancelled** (Indica si el vuelo fue cancelado)
**24. cancellation_code** (Código del motivo de cancelación del vuelo)
**25. diverted** (Indica si el vuelo fue desviado)
**26. crs_elapsed_time** (Duración programada del vuelo)
**27. actual_elapsed_time** (Duración real del vuelo)
**28. air_time** (Tiempo real en el aire)
**29. distance** (Distancia del recorrido del vuelo)
**30. carrier_delay** (Minutos de retraso atribuibles a la aerolínea operadora)
**31. weather_delay** (Minutos de retraso causados por condiciones meteorológicas)
**32. nas_delay** (Retraso atribuible al NAS-National Airspace System, Sistema de control de espacio aéreo)
**33. security_delay**(Retraso por razones de seguridad)
**34. late_aircraft_delay** (Retraso debido a llegada tardía de la aeronave, llegó tarde de un vuelo anterior, efecto cascada)



