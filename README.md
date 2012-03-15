Check out the [live demo][demo]!

The tutorial includes several checkpoints:

* [Blank slate][00]
* [`layout: auto`][01a] ([view diff][00-01a])
* [`layout: auto` with 'lorem ipsum'][01b] ([view diff][01a-01b])
* [`layout: fit` with 1 child component][02a] ([view diff][01b-02a])
* [`layout: fit` with 2 children][02b] ([view diff][02a-02b])
* [`layout: card` with 3 children][03] ([view diff][02b-03])
* [`Ext.TabPanel` with 3 children][04a] ([view diff][03-04a])
* [`Ext.TabPanel` with customized card switch transition][04b] ([view diff][04a-04b])
* [`Ext.Carousel` with 3 children][05a] ([view diff][04b-05a])
* [`Ext.Carousel` with `direction: 'vertical'`][05b] ([view diff][05a-05b])
* [`layout: vbox`][06a] ([view diff][05b-06a])
* [`layout: vbox` with `pack: 'center'`][06b] ([view diff][06a-06b])
* [`layout: vbox` with `defaults: {flex: 1}`][06c] ([view diff][06b-06c])
* [`layout: hbox` with `defaults: {flex: 1}`][06d] ([view diff][06c-06d])
* [Traffic light carousels][07] ([view diff][06d-07])
* [Exquisite corpse game][08a] ([view diff][07-08a])
* [Exquisite corpse game with credits][08b] ([view diff][08a-08b])
* [Exquisite corpse game with docked credits][08c] ([view diff][08b-08c])

## Using this repository to [follow the screencast][video]

First, you'll have to clone this repository:

    git clone git://github.com/senchalearn/Exquisite-layouts.git

Change into the directory:

    cd Exquisite-layouts

By default, the git clone command will only create the master branch locally. If you want to study the code at each checkpoint, you will have to fetch each of the other branches. You can do so by running the following:

    git checkout -b 00_blank_slate origin/00_blank_slate
    git checkout -b 01a_auto_layout origin/01a_auto_layout
    git checkout -b 01b_auto_layout origin/01b_auto_layout
    git checkout -b 02a_fit_layout origin/02a_fit_layout
    git checkout -b 02b_fit_layout origin/02b_fit_layout
    git checkout -b 03_card_layout origin/03_card_layout
    git checkout -b 04a_tab_panel origin/04a_tab_panel
    git checkout -b 04b_tab_panel origin/04b_tab_panel
    git checkout -b 05a_carousel origin/05a_carousel
    git checkout -b 05b_carousel origin/05b_carousel
    git checkout -b 06a_box_layout origin/06a_box_layout
    git checkout -b 06b_box_layout origin/06b_box_layout
    git checkout -b 06c_box_layout origin/06c_box_layout
    git checkout -b 06d_box_layout origin/06d_box_layout
    git checkout -b 07_traffic_light_carousel origin/07_traffic_light_carousel
    git checkout -b 08a_exquisite_corpse origin/08a_exquisite_corpse
    git checkout -b 08b_exquisite_corpse origin/08b_exquisite_corpse
    git checkout -b 08c_exquisite_corpse origin/08c_exquisite_corpse

[demo]: http://senchalearn.github.com/Exquisite-layouts/
[video]: https://vimeo.com/album/1846874/video/38128757

[00]:   https://github.com/senchalearn/Exquisite-layouts/tree/00_blank_slate
[01a]:  https://github.com/senchalearn/Exquisite-layouts/tree/01a_auto_layout
[01b]:  https://github.com/senchalearn/Exquisite-layouts/tree/01b_auto_layout
[02a]:  https://github.com/senchalearn/Exquisite-layouts/tree/02a_fit_layout
[02b]:  https://github.com/senchalearn/Exquisite-layouts/tree/02b_fit_layout
[03]:   https://github.com/senchalearn/Exquisite-layouts/tree/03_card_layout
[04a]:  https://github.com/senchalearn/Exquisite-layouts/tree/04a_tab_panel
[04b]:  https://github.com/senchalearn/Exquisite-layouts/tree/04b_tab_panel
[05a]:  https://github.com/senchalearn/Exquisite-layouts/tree/05a_carousel
[05b]:  https://github.com/senchalearn/Exquisite-layouts/tree/05b_carousel
[06a]:  https://github.com/senchalearn/Exquisite-layouts/tree/06a_box_layout
[06b]:  https://github.com/senchalearn/Exquisite-layouts/tree/06b_box_layout
[06c]:  https://github.com/senchalearn/Exquisite-layouts/tree/06c_box_layout
[06d]:  https://github.com/senchalearn/Exquisite-layouts/tree/06d_box_layout
[07]:   https://github.com/senchalearn/Exquisite-layouts/tree/07_traffic_light_carousel
[08a]:  https://github.com/senchalearn/Exquisite-layouts/tree/08a_exquisite_corpse
[08b]:  https://github.com/senchalearn/Exquisite-layouts/tree/08b_exquisite_corpse
[08c]:  https://github.com/senchalearn/Exquisite-layouts/tree/08c_exquisite_corpse

[00-01a]: https://github.com/senchalearn/Exquisite-layouts/compare/00_blank_slate...01a_auto_layout
[01a-01b]: https://github.com/senchalearn/Exquisite-layouts/compare/01a_auto_layout...01b_auto_layout
[01b-02a]: https://github.com/senchalearn/Exquisite-layouts/compare/01b_auto_layout...02a_fit_layout
[02a-02b]: https://github.com/senchalearn/Exquisite-layouts/compare/02a_fit_layout...02b_fit_layout
[02b-03]: https://github.com/senchalearn/Exquisite-layouts/compare/02b_fit_layout...03_card_layout
[03-04a]: https://github.com/senchalearn/Exquisite-layouts/compare/03_card_layout...04a_tab_panel
[04a-04b]: https://github.com/senchalearn/Exquisite-layouts/compare/04a_tab_panel...04b_tab_panel
[04b-05a]: https://github.com/senchalearn/Exquisite-layouts/compare/04b_tab_panel...05a_carousel
[05a-05b]: https://github.com/senchalearn/Exquisite-layouts/compare/05a_carousel...05b_carousel
[05b-06a]: https://github.com/senchalearn/Exquisite-layouts/compare/05b_carousel...06a_box_layout
[06a-06b]: https://github.com/senchalearn/Exquisite-layouts/compare/06a_box_layout...06b_box_layout
[06b-06c]: https://github.com/senchalearn/Exquisite-layouts/compare/06b_box_layout...06c_box_layout
[06c-06d]: https://github.com/senchalearn/Exquisite-layouts/compare/06c_box_layout...06d_box_layout
[06d-07]: https://github.com/senchalearn/Exquisite-layouts/compare/06d_box_layout...07_traffic_light_carousel
[07-08a]: https://github.com/senchalearn/Exquisite-layouts/compare/07_traffic_light_carousel...08a_exquisite_corpse
[08a-08b]: https://github.com/senchalearn/Exquisite-layouts/compare/08a_exquisite_corpse...08b_exquisite_corpse
[08b-08c]: https://github.com/senchalearn/Exquisite-layouts/compare/08b_exquisite_corpse...08c_exquisite_corpse
