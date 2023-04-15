```php
<?php 

namespace AlexPedrasa;

class About extends Me
{

    public function getCurrentWorkplace()
    {
        return [
            'workplace' => [
                'company' => 'Suth Hive',
                'position' => 'Backend Developer',
                'seniority' => 'Semi Senior',
            ]
        ];
    }
    
    public function getSkills()
    {
        return [
            Php::class,
            Laravel::class,
            Sql::class,
            MongoDB::class,
            Javascript::class,
            NodeJS::class,
            Vuejs::class,
            Angular::class,
            React::class,
            TailwindCss::class,
            Azure::class,
            RabbitMQ::class,
            Redis::class
        ];
    }
}
```
