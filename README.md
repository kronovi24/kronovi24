```php
<?php

namespace KurtsCanoy;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Provincial ICT Unit, Surigao Del Norte',
                'position' => 'Computer Programmer'         
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
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To gain more experience and knowledge, Be one of the Best';
    }
}
```
