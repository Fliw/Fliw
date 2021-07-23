```php
<?php

namespace Fliw;

class About extends Me
{
    /**
     * Display current life motives.
     *
     * @param null
     * @return string
     */
    public function getCurrentProfile(): string {
        return 'an Ordinary Young Web Developer who want to help each other to be coder!';
    }
    
    /**
     * Display user's 'secret' detail.
     *
     * @param null
     * @return array
     */
    private function getProfilingDetail(): array {
        return [
            'age' => 20,
            'phone' => '+628812671057',
            'email' => 'Fliw@DigitalKode.com'
        ];
    }
    
    /**
     * Display current workplaces.
     *
     * @param null
     * @return array
     */
    public function getCurrentWorkplace(): array {
        return [
            'workplace' => 
              [
                'company' => 'PT. Ide Jualan Creative',
                'position' => 'Founder & CTO'         
              ],
              [
                'company' => 'PT. Naisha Inspirasi Muslimah',
                'position' => 'Lead Developer'
              ],
              [
                'company' => 'Digital Kode',
                'position' => 'Co-Founder'
              ]
        ];
    }

    /**
     * Display Skills & Knowledge.
     *
     * @param null
     * @return array of class
     */
    public function getDailyKnowledge(): array {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            ReactJs::class,
            Docker::class,
            MySql::class,
            TailwindCss::class
        ];
    }
}
```
<p float="left">
  <img src="https://github-profile-trophy.vercel.app/?username=fliw&row=2&column=4&theme=onedark#1" width="60%">
  <img src="https://github-contribution-stats.vercel.app/api/?username=fliw#1" width="38%" />
</p>


                                      
