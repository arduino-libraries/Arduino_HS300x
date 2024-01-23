# Arduino_HS300x

## Methods

### `begin()`

#### Description

Initializes the library for the HS300x sensor.

#### Syntax

```
HS300x.begin()
```

#### Parameters

None.

#### Returns

- `1` on success.
- `0` on failure.

### `end()`

#### Description

Deinitializes the library, ending the I2C communication. 

#### Syntax

`HS300x.end()`

#### Parameters

None.

#### Returns

Nothing.

### `readTemperature()`

#### Description

Reads the temperature in either Celsius or Fahrenheit. Default reading is Celsius.

#### Syntax

```
HS300x.readTemperature(CELSIUS) // Celsius reading
HS300x.readTemperature(FAHRENHEIT) // Fahrenheit reading
```

#### Parameters

- `FAHRENHEIT` 
- `CELSIUS`

#### Returns

- `float` - temperature in specified unit. 

### `readHumidity()`

#### Description

Reads the relative humiditiy of the HS300x sensor.

#### Syntax

```
HS300x.readHumidity()
```

#### Parameters

None.

#### Returns

- `float` - relative humdidity.