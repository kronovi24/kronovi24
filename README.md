```php
<?php

namespace KurtsCanoy;

class About extends Me
{
    public function getWorkExperience(): array
    {
        return [
            [
                'company' => 'Provincial ICT Office, Surigao del Norte',
                'position' => 'Computer Programmer',
                'year' => '2024 - 2026'
            ],
            [
                'company' => 'Provincial ICT Unit, Surigao del Norte',
                'position' => 'Administrative Aide II',
                'year' => '2023 - 2023'
            ],
            [
                'company' => 'Freelance',
                'position' => 'Full Stack & Embedded Systems Developer',
                'year' => '2021 - 2023'
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Bootstrap::class,
            Mysql::class,
            TailwindCss::class,
            Jquery::class,
            VueJs::class
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To gain more experience and knowledge, Be one of the Best';
    }
}
```
