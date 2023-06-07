<?php

namespace RyzXD;

class About extends Me

{

    public function getCurrentWorkplace(): array

    {

        return [

            'workplace' => [

                'company' => 'Ryz-Store',

                'position' => 'Founder'         

            ]

        ];

    }

    public function getDailyKnowledge(): array

    {

        return [

            my::class,

        ];

    }

    public function getFutureGoal(): string

    {

        return 'To contribute to open source.';

    }

}
