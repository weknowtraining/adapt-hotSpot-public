# adapt-hotSpot

A hotspot component where learner must select the correct pins.

##Installation


First, be sure to install the [Adapt Command Line Interface](https://github.com/adaptlearning/adapt-cli), then from the command line run:-

        adapt install adapt-hotSpot

This component can also be installed by adding the component to the adapt.json file before running `adapt install`:

        "adapt-hotSpot": "*"

##Usage

To Be Updated

##Settings overview

An complete example of this components settings can be found in the [example.json](https://github.com/BATraining/adapt-hotSpot/blob/master/example.json) file. A description of the core settings can be found at: [Core model attributes](https://github.com/adaptlearning/adapt_framework/wiki/Core-model-attributes)

Further settings for this component are:

####_component

This value must be: `hotSpot`

####_classes

You can use this setting to add custom classes to your template and LESS file.

####_layout

This defines the position of the component in the block. Values can be `full`, `left` or `right`. 

####_attempts

Default: `1`

Specifies the number of attempts for this question.

####_isRandom

Default: `false`

Setting this value to `true` will cause the `_items` to appear in a random order each time this component is loaded.

####_selectable

Defines the number of `_items` that can be selected.

####_backgroundImage

The backgroundImage represents hotSpot background image and contains `url`.

####large

Enter a path to the image for large device width. Paths should be relative to the src folder, e.g.

####small

Enter a path to the image for small device width. Paths should be relative to the src folder, e.g.

####_items

Each item represents one choice for the multiple choice question and contains `_left`, `_top`, `_shouldBeSelected` and `_graphic`.

####_shouldBeSelected

Value can be `true` or `false`. Use `true` for items that must be selected for a correct answer. The value of `_selectable` must correspond to the number of `_items` where `_shouldBeSelected` is set to `true`.

####_graphic

The image for this multiple choice option is defined within this element. This element should contain only one value for `alt`, `title`, `large` and `small`.

####alt

The alt setting provides alternative information for the image.

####large

Enter a path to the image for large device width. Paths should be relative to the src folder, e.g.

course/en/images/gqcq-1-large.gif

####small

Enter a path to the image for small device width. Paths should be relative to the src folder, e.g.

course/en/images/gqcq-1-small.gif

####_width

Enter width of hotSpot.

####_height

Enter height of hotSpot.

####_top

Set top of hotSpot.

####_left

Set left of hotSpot.

####_mobilewidth

Set mobile width of hotSpot for small backgroundImage.

####_mobileheight

Set mobile height of hotSpot for small backgroundImage.

####_mobiletop

Set mobile top of hotSpot for small backgroundImage.

####_mobileleft

Set mobile left of hotSpot for small backgroundImage.

##Limitations

None

##Browser spec

This component has been tested to the standard Adapt browser specification.
