# Rearranger
 FL Studio Edison Audio Script which chops and rearranges audio based on peak and average loudness.


![Rearrange - Add Markers](https://github.com/Everither/rearranger/assets/122586326/af03990c-1ce0-4baa-87f2-b5b4baecd29b)


![Rearrange - Rearrange](https://github.com/Everither/rearranger/assets/122586326/a22d78ae-655f-4365-a8be-88613d94d717)

## Installation

Place `Rearrange.pyscript` inside `...\Documents\Image-Line\FL Studio\Settings\Audio scripts`

Run the script by opening Edison, go to `Tools` > `Run script` > `Rearrange`

For further information, please visit the official [FL Studio Edison Script Reference.](https://www.image-line.com/fl-studio-learning/fl-studio-online-manual/html/plugins/editortool_run.htm)
 

## Parameters - Add Markers
 
`BPM` Tempo for chopping audio. 

`Division` Length of each region in musical time. 

`Noise` Random offset for marker placement. 

`Seed` Seed for pseudorandom generation.

## Parameters - Rearrange

`Direction` Ascending or descending order for arranging regions. 

`Sort By` Criterion for sorting: Peak, Average Peak, or Reverse. 

`Declick` Fade duration of the beginning and end of each chop.

`Delete Markers` Option to keep or delete markers.

## Example 1 - No Markers In Original Audio



https://github.com/Everither/rearranger/assets/122586326/1e5203aa-1518-471f-bd77-13f29780984a


