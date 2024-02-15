# 3Dhover1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
            margin: 0;
            padding: 0;
            font-family: 'Courier New', Courier, monospace;
            box-sizing: border-box;
        }
        body{
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background: #6b6b6b;
        }
        .container{
            width: 1000px;
            position: relative;
            display: flex;
            justify-content: space-between;
        }
        .container .card{
            position: relative;
            width: 300px;
            height: 200px;
        }
        .container .card .face{
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            transition: 1.5s;
        }
        .container .card .face.face1{
            background: #ffffff;
            display: flex;
            justify-content: center;
            align-items: center;
            z-index: 1;
            transform-origin: bottom;
        }
        .container .card .face.face1 img{
            max-width: 150px;
        }
        .container .card .face.face1 h3{
            margin: 10px 0 0;
            color: #fff;
            text-align: center;
            font-size: 1.5rem;
        }
        .container .card:hover .face.face1{
            transform: translateY(-100%) rotateX(90deg);
            background: #ff0057;
        }
        .container .card .face.face2{
            background: #3dff98;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
            transform-origin: top;
            transform: translateY(100%) rotateX(90deg);
        }
        .container .card:hover .face.face2{
            transform: translateY(0) rotateX(0);
        }
        </style>
</head>
<body>
    <div class="container">
        <div class="card">
            <div class="face face1">
                <div class="content">
                    <img src="https://th.bing.com/th/id/OIP.MokZkJ5a4pCqkPqu6R-qEQHaE-?pid=ImgDet&rs=1" alt="Spider-Woman" style="mix-blend-mode: multiply;">
                </div>
                <h2>Spider-Woman</h2>
            </div>
            <div class="face face2">
                <div class="content">
                    <p>
                        Science bites, spiders electrify - Spider-Women swing through realities! Jessica unravels mysteries, Gwen blasts venom, Mayday carries the torch. Each leaps beyond fate, proving everyone, not just Peter, can weave webs of heroics. 
                    </p>
                </div>
            </div>
        </div>
        
        <div class="card">
            <div class="face face1">
                <div class="content">
                    <img src="https://th.bing.com/th/id/OIP.yfw6VcyjRHyL9_nGpX0XOAHaHp?pid=ImgDet&rs=1" alt="Thor" style="mix-blend-mode: multiply;">
                </div>
                <h2>Thor</h2>
            </div>
            <div class="face face2">
                <div class="content">
                    <p>
                        Thor thunders through myth and Marvel, wielding his hammer against giants and grappling with himself. Impulsive, yet noble, he defends Asgard and cracks jokes with the Avengers, a storm of power with a hero's heart.
                    </p>
                </div>
            </div>
        </div>
        
        <div class="card">
            <div class="face face1">
                <div class="content">
                    <img src="https://th.bing.com/th/id/OIP.k_sgLHGrOkYvnLm2tG1l0gHaEv?pid=ImgDet&rs=1" alt="Dr.Strange" style="mix-blend-mode: multiply;">
                </div>
                <h2>Dr.Strange</h2>
            </div>
            <div class="face face2">
                <div class="content">
                    <p>
                        Once a surgeon, now Sorcerer Supreme, Stephen Strange wields mystical arts as a shield against interdimensional threats. From astral planes to city streets, his spells bend reality, battling cosmic horrors with wit and arcane might.
                    </p>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
