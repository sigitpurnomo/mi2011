<?php 
$grid=array(
    array('nama'=>'Sigit', 'id'=>'MI'), 
    array('nama'=>'Purnomo', 'id'=>'TI'),
    array('nama'=>'Amrian', 'id'=>'MI'),
    array('nama'=>'Jono', 'id'=>'Sipil'),
    array( 'nama'=>'Jackson', 'id'=>'Elektro'),
);
         
$result=new CArrayDataProvider($grid, array(
    'id'=>'id', 
    'sort'=>array(
        'attributes'=>array( 
            'id', 'nama',
        ),
    ),
));
$this->widget('zii.widgets.grid.CGridView', array('dataProvider'=>$result,'columns'=>array(
            array(
                'name'=>'Nama',
                'value'=>'$data["nama"]',
            ),
            array( 
                'name'=>'Jurusan',
                'value'=>'$data["id"]',
            ),
        ),
));
?> 
