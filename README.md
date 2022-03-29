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
                'position' => 'Co-Founder & CTO'         
              ],
              [
                'company' => 'PT. Naisha Inspirasi Muslimah',
                'Position' => 'Lead Engineer & Code Reviewer'
              ],
              [
                'company' => 'Kampusjualan by Idejualan',
                'Position' => 'Lead IT Engineer'
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
            PHP::class,
            JavaScript::class,
            TypeScript::class,
            MySql::class,
            MongoDB::class,
            Java::class,
            CPlusPlus::class,
            CSharp::class,
            Dart::class,
            Python::class
        ];
    }
}
```
<p float="left">
  <img src="https://github-profile-trophy.vercel.app/?username=fliw&row=2&column=4&theme=onedark#1" width="60%">
  <img src="https://github-contribution-stats.vercel.app/api/?username=fliw#1" width="38%" />
</p>


                                      
