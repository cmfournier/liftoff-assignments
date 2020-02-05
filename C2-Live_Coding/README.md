# Live Coding

using System;

namespace Final_Live_Coding
{
    class Program
    {
        static void Main(string[] args)
        {
            int num_treaters = 250;
            int tot_pieces = num_treaters * 3;
            int temp;
            string[] weather_types = { "Clear", "Cloudy", "Raining", "Full Moon" };
            var clear_total;
            var cloudy_total;
            var rainy_total;
            var full_moon_total;

            if (weather_type = "Clear")
            {
                clear_total = tot_pieces + { tot_pieces * .10};
            }
            else if (weather_type = "Cloudy")
            {
                cloudy_total = tot_pieces;
            }
            else if (weather_type = "Raining")
            {
                rainy_total = tot_pieces - { tot_pieces * .25}
            }
            else
            {
                full_moon_total = tot_pieces + { tot_pieces * .25}
            }

            Console.WriteLine("Enter temp");
            if (temp > 40)
            {

            }

        
    }
}

/*"""Halloween is coming, and you need to figure out how much candy to buy.Luckily you have tracked the weather, temperature, 
 * and number of tricker treaters from years past.From your research you have tracked 4 different types of weather: "Clear", "Cloudy", 
 * "Raining", "Full Moon"
 * You get 10% more trick or treaters if the weather is clear
 * You get 0% more trick or treaters if the weather is cloudy
 * You get 25% less trick or treaters if the weather is rainy
 * You get 25% more trick or treaters if the weather is Full Moon
 * 
 *  * From your research you have tracked 4 differnt types of temperature: 40s, 50s, 60s, 70s
 * You get more trick or treaters the warmer the weather'
 * You get 5% less trick or treaters if it's in the 40s
 * You get 0% more trick or treaters if it's in the 50s
 * You get 5% more trick or treaters if it's in the 60s
 * You get 20% more trick or treaters if its' in the 70s
 * 
 * On average you get 250 trick or treaters, and you want to give each kid 3 pieces of candy.
 * How much candy do you need to buy if it's clear, and in the 50s?825
 * How much candy do you need to buy if it's a full moon, and in the 40s?900
 * How much candy do you need to buy if it's raining, and in the 70s?712.5"""*/
