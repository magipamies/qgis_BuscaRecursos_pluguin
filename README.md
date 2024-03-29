# ![](icon/icon.png) BuscaRecursos #


BuscaRecursos is a QGis plugin to look for city amenities near a defined
facility.
Given a circular area defined by a facility (center) and a maximum distance
(radius), plugin generates a points layer over OpenStreetMap map with all the
target amenity instances found inside this area.

When "BuscaRecursos" is launched it will open a dialog from where the user can
set and execute the pluggin. Configurable variables are:
- City name
- Search criteria (amenity).
- Maximum distance (target zone radius).
- Facility type (amenity).
- Facility name.


![](icon/formulari2.png)


## Installation

### Via plugins menu
The easier way to install it is using the QGIS Plugin Manager:
- Open to the Qgis `Plugins` menu.
- Click to  `Manage and install plugins`.
- Search for `BuscaRecursos` into the `All` section.

Once installed, it will be available in the `Plugins` menu and the `Plugins toolbar`.

### Manually

Copy the pluggins files into <QGIS Python plugins directory>/`BuscaRecursos` folder.

*Windows note:* The QGIS plugin directory should be under `C:\Documents and Settings\<Username>\.qgis2\python\plugins\` (Windows XP) or `C:\Users\<Username>\.qgis2\python\plugins\` (Windows +7).

*QGIS 1.8 note:* QGIS 1.8 stores its config into the `.qgis` directory.

Once the plugin is loaded into the python directory:
- Enable it from the list.
- Open it from the plugins menu.

### Via git

Clone the repository into your QGIS python plugins directory:

    cd ~/.qgis2/python/plugins/
    git clone https://github.com/magipamies/qgis_BuscaRecursos_pluguin.git BuscaRecursos

## Source code

Read more in: [https://github.com/magipamies/qgis_BuscaRecursos_pluguin](https://github.com/magipamies/qgis_BuscaRecursos_pluguin)


## Issue Tracker

Don't hesitate to report your issues, ideas and enhancements! [https://github.com/magipamies/qgis_BuscaRecursos_pluguin/issues](https://github.com/magipamies/qgis_BuscaRecursos_pluguin/issues)


### Contact

Magí Pàmies Sans: *magipamies@gmail.com*  

## License

BuscaRecursos is a free/libre software that's licensed under the GNU General Public License.
