<!--
 * @Author: ferried
 * @Email: harlancui@outlook.com
 * @Date: 2020-09-24 11:13:00
 * @LastEditTime: 2020-09-24 11:42:59
 * @LastEditors: ferried
 * @Description: Basic description
 * @FilePath: /rymcu-mcu-databases/README.md
 * @LICENSE
-->

# rymcu-mcu-databases

Database that holds basic MCU information.

# How to use

```npm
npm install rymcu-mcu-databases
```

```js
const md = new MCUDatabases()
find_model(magic: number): MCUModel
add_model(models: Array<MCUModel>)
get_databases():Array<MCUModel>
print_model_info(model: MCUModel):void
```
