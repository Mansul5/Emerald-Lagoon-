<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Les profondeurs du lac d'Emerald Lagoon</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,700;1,400&display=swap');
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Playfair Display', serif;
            line-height: 1.6;
            
            min-height: 100vh;
            padding: 2rem;
            color: #eafa06;
        
            
  background: url("pexels-media-931018.jpeg") center;
  background-size: cover;



        }


        

        .container {
            max-width: 800px;
            margin: 0 auto;
            background: rgba(255, 255, 255, 0.95);
            padding: 2rem;
            border-radius: 1rem;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .title {
            text-align: center;
            color: #1a2a6c;
            margin-bottom: 2rem;
            font-size: 2.5rem;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.1);
        }

        .chapter {
            display: none;
            opacity: 0;
            transition: opacity 0.5s ease;
            border: 2px solid rgba(255, 255, 255, 0.5);
background-color: rgba(0, 0, 0, 0.6);
border-radius: 10px;
color: white;
text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.8);
max-width: 600px;
box-shadow: 0 4px 8px rgba(0, 0, 0, 0.5);
padding: 20px ;
margin: 20px;
            
    
            
            
           
        }

        .chapter.active {
            display: block;
            opacity: 1;
        }

        .navigation {
            display: flex;
            justify-content: space-between;
            margin-top: 2rem;
            padding-top: 1rem;
            border-top: 2px solid #eee;
        }

        .btn {
            background: #1a2a6c;
            color: white;
            border: none;
            padding: 0.5rem 1rem;
            border-radius: 0.25rem;
            cursor: pointer;
            transition: background 0.3s ease;
        }

        .btn:hover {
            background: #2a3a7c;
        }

        .btn:disabled {
            background: #ccc;
            cursor: not-allowed;
        }

        .chapter-title {
            color: #f80a0a;
            margin: 1.5rem 0;
            font-size: 1.8rem;
        }

        p {
            margin-bottom: 1rem;
            text-align: justify;
        }

        .quote {
            font-style: italic;
            color: #8b0202;
            border-left: 3px solid #b21f1f;
            padding-left: 1rem;
            margin: 1rem 0;
        }

        #progress-bar {
            width: 100%;
            height: 4px;
            background: #eee;
            margin: 1rem 0;
            border-radius: 2px;
        }

        #progress-fill {
            height: 100%;
            background: #1a2a6c;
            width: 0%;
            transition: width 0.3s ease;
            border-radius: 2px;
        }

        .song-section {
            background: rgba(26, 42, 108, 0.1);
            padding: 1.5rem;
            border-radius: 0.5rem;
            margin: 1.5rem 0;
            position: relative;
            transition: all 0.3s ease;
        }

        .song-section:hover {
            background: rgba(26, 42, 108, 0.15);
        }

        .audio-player {
            width: 100%;
            margin-top: 1rem;
            border-radius: 1rem;
        }

        .audio-player::-webkit-media-controls-panel {
            background: rgba(255, 255, 255, 0.9);
        }

        .song-title {
            color: #1a2a6c;
            font-style: italic;
            margin-bottom: 0.5rem;
            font-weight: bold;
        }

        .lyrics {
            font-style: italic;
            color: #faf7f7;
            margin: 1rem 0;
            padding-left: 1rem;
            border-left: 3px solid #b21f1f;
        }

        @keyframes waterWave {
            0% { transform: translateY(0); }
            50% { transform: translateY(-5px); }
            100% { transform: translateY(0); }
        }

        .water-effect {
            animation: waterWave 3s ease-in-out infinite;
            display: inline-block;
        }

        .music-icon {
            position: absolute;
            right: 1rem;
            top: 1rem;
            color: #f8f8f8f8;
            opacity: 0.6;
        }

        
            
            .image-container {
  display: flex;
  overflow: hidden;
  animation: slide 10s infinite;
  width: 100%;
  height: 300%;
}

.image-container img {
  width: 100%;
  height: auto;
  flex-shrink: 0; 
  width: 100%;
  height: auto;
}
.image-container {
    animation: slide 12s infinite;
}
@keyframes slide {
  0% {
    transform: translateX(0);
  }
  33% {
    transform: translateX(-100%);
  }
  66% {
    transform: translateX(-200%);
  }
  100% {
    transform: translateX(0);
  }
}
h2{
    color:#b21f1f
    
}
    </style>
</head>
<body>
    <div class="container">
        <h1 class="title">
            <span class="water-effect">Dans les profondeurs du lac</span><br>
            d'Emerald Lagoon village
        </h1>
        <h2>Une histoire d'amour atypique</h2>

        <div id="progress-bar">
            <div id="progress-fill">
        </div>
        
          
        <div class="chapter-container">
            <div class="image-container">
                <img src="Screenshot_20231214-120141~2.jpg" alt="Image 1">
              <img src="Screenshot_20231214-170209~2.jpg" alt="Image 1">
              <img src="Screenshot_20231214-234947~2.jpg" alt="Image 2">
              <img src="Screenshot_20231215-132624~2.jpg" alt="Image 3">
              </div>
            
    
        <div class="chapter active" id="chapter1">
            <h2 class="chapter-title">PARTIE I : La naissance d'un nouveau sambaar</h2>
            <p>Au cœur d'Emerald Lagoon, là où les eaux scintillent d'une teinte émeraude sous les rayons du soleil, naissait un phénomène rare et mystique : l'Œuf d'Akara. Depuis le début du siècle nouveau, sa présence captivait les habitants des profondeurs marines. <br><br>Chaque jour, l'œuf grandissait, émettant une lueur magique qui illuminait les abysses environnants. <br><br>
                Les poissons curieux s'assemblaient en un ballet aquatique, contemplant ce prodige qui renfermait le plus grand mystère d'Emerald Lagoon. <br><br>
                
                Le grand jour était enfin arrivé.
                L'Œuf d'Akara, baigné de la lueur émeraude tant attendue, commença à émettre des vibrations douces. Autour de lui, les poissons de toutes formes et tailles se rassemblèrent, leurs écailles chatoyant sous la lumière magique. <br><br>
                Les Dorados, majestueux dans leur éclat doré, se rapprochèrent avec une grâce élégante. <br>
                Les Mérous, silencieux gardiens des profondeurs, s'approchèrent avec respect. <br>
                Même les espiègles poissons-clowns, d'ordinaire facétieux, se calmèrent devant l'événement solennel. <br>
                
                Un à un, les autochtones d'Emerald Lagoon se figèrent en une danse silencieuse, tandis que l'œuf frémissait de plus en plus. <br>
                Puis, dans un éclat final, l'œuf s'ouvrit, libérant Sambaar dans un tourbillon de magie. Les poissons, ébahis, observèrent ce triton mystérieux faire son entrée dans le monde avec une aura enchanteresse, réalisant que l'attente de dix-huit cycles de marée avait enfin abouti. <br><br>
                
                Le pendentif qui pendait au cou du nouvel habitant du lac s'illumina, révélant au jeune triton son prénom. <br>
                
                Tu es Sambaar, centième porteur de ce nom. Te voilà enfin mature, prêt à affronter le monde en dehors du giron protecteur d'Akara, résonna une voix fantomale qui troubla l’esprit encore sensible de Sambaar. <br> <br>
                
                Les spectateurs le lorgnaient étrangement, intrigués par son apparence. <br>
                En effet, Sambaar était mi-humain, mi-poisson, avec un teint marron éclatant, des dreadlocks roux, et une queue verte dont les écailles luisaient de teintes multiples. <br>
                
                Le jeune triton sourit à l'attroupement et les salua joyeusement d'un signe de la main. <br>
                Ils lui rendirent son salut et lui souhaitèrent la bienvenue parmi eux. <br><br>
                
                Une morue brune s'avança tout à coup et tourna autour du triton avant de s'exclamer : <br><br>
                « Qu'est-ce que tu ressembles à Coraillie! Sauf qu'elle a une peau d'eau réactive, ce qui n'est pas ton cas… Hum… tu ressembles plutôt à un poisson-lanterne. » <br><br>
                
                « Qui est Coraillie ? », demanda Sambaar. <br><br>
                
                « C'est la star des océans ! Elle est une Aqualuminis, la seule de sa race, un peu comme toi. Son refuge est le Sanctuaire des Perles, un endroit fascinant où les coraux s'épanouissent. Suis-moi, je vais te conduire à elle. » <br><br>
                
                À ces mots, la morue guida Sambaar dans une direction particulière. Pendant ce temps, les autres poissons se dispersèrent, reprenant leurs activités d'antan. <br><br>
                
                Sambaar découvrit pour la première fois les merveilles de l'océan. <br>
                Il rencontra des créatures fantastiques : <br><br>
                
                Les Aqualuxias, êtres possédant une bioluminescence féerique ; <br>
                
                Les Écaillesirènes, aux chants envoûtants ; malgré leur petite taille, leurs voix perçaient les horizons ; <br>
                
                Les Spectracoraux, semblables à des lanternes sous-marines ; leur lumière formait des radiations géométriques selon leurs mouvements; <br>
                
                Et enfin, les Vagueshapers, parmi les créatures les plus intimidantes, capables de modeler les vagues à leur guise grâce à leurs tourbillonnements. <br>
                
                
                Sambaar restait interdit face à ces spectacles bluffants. <br><br>
                
                « Crois-moi, tu t'habitueras! La Clairière des Algues est le lieu le plus énergique d'Emerald Lagoon », déclara la morue. <br>
                
                Notre protagoniste se demandait à quoi pouvait ressembler Coraillie. <br>
                La description de la morue avait suffi à éveiller une curiosité grandissante. <br>
                
                Lorsqu'ils atteignirent le Sanctuaire des Perles, le cœur de Sambaar battait à tout rompre. L’adrénaline montait rien qu’en voyant le rayonnement diaphane des majestueux coraux encastrés dans des pierres précieuses, les algues dansantes, et les murmures suaves d’un timbre ensorcelant. <br><br>
                
                « Nous y voilà. Bienvenue dans le Sanctuaire des Perles! Ce site est le joyau de notre cité hadale. », annonça la morue. <br>
                
                « Où est-elle? », s'impatienta le triton, promenant son regard dans tous les sens, sa nageoire crispée par l’angoisse. <br><br>
                
                C'est alors qu'une élégante créature colorée de lueurs éthérées et vêtue de corail apparut devant lui. <br><br>
                
                « Qui es-tu, étrange étranger  ? », interrogea Coraillie, méfiante. <br><br>
                
                « Coraillie, enfin te voilà  ! Je te présente le centième Sambaar. Il vient juste de naître. » <br><br>
                
                « Ha ha  ! Quel drôle de bébé tu fais  ! Félicite-toi pour ta naissance phénoménale  ! Moi, à ma naissance, j’avais la taille de cette perle de rubis  ! », indiqua-t-elle du doigt.
                
                Sambaar la trouva marrante et décontractée, loin du monstre qu’il s’était imaginé. <br><br>
                
                Coraillie, en réalité, était une femmoïde d’une beauté singulière, incarnant l’élégance des profondeurs marines. Sa peau translucide émettait une lueur douce, rappelant les reflets des perles délicates qui ornaient les fonds marins. Ses parures de corail, délicatement tissées dans sa chevelure aquatique, ajoutaient une touche artistique à sa présence, faisant d’elle une énigme vivante dans le royaume sous-marin. <br><br>
                
                Sambaar sentait qu’il allait bien s’entendre avec elle. Déjà, une sympathie hors pair les liait. <br>
                Le jeune homme-poisson observa intensément la femme-corail. Il essaya de la toucher, mais sa main traversa la peau de Coraillie. <br>
                
                C’était une sensation extraordinaire, surtout que l’Aqualuminis généra plusieurs couleurs au simple toucher. <br>
                
                Ils se regardèrent et s’invitèrent dans un jeu de danse circulaire. <br>
                
                Cette rencontre sibylline allait marquer la naissance d’une amitié entre deux héritiers de races perdues. <br>
                
                </p>
            </div>
        
        

        <div class="chapter" id="chapter2">
            <h2 class="chapter-title">PARTIE II : Ndiémé</h2>
            <p>En dehors de l'univers aquatique d'Emerald Lake, s'étendait le village verdoyant d'Emerald. Les Éméraldiens, une population très active, animaient chaque matin les marchés, les foires regorgeant de tissus aux couleurs explosives, , les ports de pêche, ainsi que les lacs et cours d’eau où les femmes lavaient leurs habits et ustensiles. <br><br>

                Parmi ces femmes habituées du lac Naane, se trouvait une jeune demoiselle de 17 ans, portant le prénom de Ndiémé.
                Dans le village, elle était connue pour ses traits charmants et sa bonne humeur débordante. Les aînés l’admiraient pour son affabilité, tandis que les garçons la convoitaient : bergers, cultivateurs, marchands de tissus ou conducteurs de charrettes, tous étaient à ses trousses.<br><br>
                
                Heureusement pour elle, l’ombre de sa mère la couvrait en permanence. Elles étaient inséparables, comme si elles étaient l’une sur les basques de l’autre.<br><br>
                Maman-Rabie, au caractère fort et légendaire, inspirait une crainte respectueuse chez les prétendants. Ces derniers redoutaient sa colère et évitaient de s’attirer sa foudre.<br><br>
                
                Ndiémé, ainsi protégée, était perçue comme un véritable Graal. Mais sa quête restait inachevée pour tous. <br><br>
                
                La mère de Ndiémé travaillait comme vendeuse de légumes frais au marché Kibaro. Ses étals étaient très prisés par les ménagères, car Maman-Rabie ne plaisantait pas avec la qualité. Elle inspectait chaque légume avec soin, le palpait, l’analysait, et, si nécessaire, l’inhalait pour s’assurer de sa fraîcheur.<br><br>
                
                En accompagnant sa mère partout où elle allait, Ndiémé avait hérité de cette attitude méticuleuse. Cependant, sa douceur naturelle la distinguait largement de sa mère.<br><br>
                
                Mbakhawou, le fils hautain du chef du village, avait entendu parler de Ndiémé. Depuis, il passait ses journées à la poursuivre.<br><br>
                Il lui chantait les plus illustres chansons de Mbeugël (amour), mais Ndiémé restait totalement insensible. À la place, elle ricanait sans jamais expliquer les raisons de son rire moqueur.<br><br>
                
                De nature colérique, Mbakhawou retournait chez lui, froissé et humilié.<br><br>
                
                En réalité, Ndiémé n’était pas intéressée par les garçons. Elle n’avait d’yeux que pour sa mère et ses tâches ménagères, qui, bien que pénibles, la rendaient épanouie.<br><br>
                Son endroit préféré restait le lac Naane. Elle pouvait y passer des heures à laver le linge sale, à chanter et à jouer avec l’eau douce où le soleil se mirait fièrement.<br><br>
                
                Ce matin-là, de nouveau au bord du lac Naane, notre chère protagoniste laissait libre cours à l’émoi de son cœur. Des mélodies libres et pleines d’amour jaillissaient de ses lèvres, créant un moment féérique.<br><br>
                
                Refrain :
                
                Ndiémé, Ndiémé, au bord du lac Naane,<br><br>
                Où le doux murmure de l’eau chante,<br><br>
                Mon cœur résonne au rythme de l’amour,<br><br>
                Âme sœur, je t’attends chaque jour.<br><br>
                
                
                Ayant fini de chanter et de laver, Ndiémé s’apprêtait à repartir, son panier de linge sous le bras, lorsqu’un bruit d’éclaboussures, suivi d’un mouvement ondulatoire des eaux, attira son attention.<br><br>
                
                Intriguée, elle déposa doucement son panier et s’immobilisa.<br><br>
                
                Lentement, Sambaar, un triton, fit surface. Sa tête émergea de l’eau, suivie par sa queue de poisson qui se mouvait avec vigueur.<br><br>
                
                Les yeux emplis de frayeur, Ndiémé poussa un cri strident avant de s’enfuir à toutes jambes.<br><br>
                
                Sambaar, quant à lui, resta stupéfait par l’éclat de la beauté de la jeune femme, gravée dans ses yeux malgré la brièveté de leur rencontre. Il n’avait jamais vu d’humains auparavant, et les jambes de Ndiémé, en particulier, le laissaient perplexe…<br><br><br><br>
                
                
                
                Chez elle, Ndiémé était encore sous le choc lorsque sa mère, Maman-Rabi, l’interpella :<br><br>
                « Ndiémé, où est le linge ? »
                D’un ton hésitant, la jeune fille balbutia :<br><br>
                « Il y a… il y a… au lac…»
                
                « Au lac quoi ? Parle clairement ! »<br><br>
                
                
                « Un monstre…»<br><br>
                
                Furieuse, Maman-Rabi s’exclama :<br><br>
                « Tu te moques de moi ?! C’est quoi cette histoire, Ndiémé ? Arrête tes bêtises et ramène-moi mes habits immédiatement, sinon je te corrige avec cette écumoire !»<br><br>
                
                De nature autoritaire, Maman-Rabi raccompagna sa fille à l’extérieur de la maison, son ustensile à la main.<br><br>
                « Ne reviens pas ici sans le linge ! Je ne sais pas ce que tu essaies d’inventer, mais ça ne marchera pas avec moi !»<br><br>
                
                Dépitée, Ndiémé se remit en route vers le lac. Une fois sur place, elle ramassa les vêtements éparpillés au sol. Elle se demandait comment elle allait les laver à nouveau. La tâche semblait interminable.<br><br>
                
                Lasse, elle se laissa submerger par ses émotions et se mit à pleurer.<br><br>
                
                Dans les profondeurs du lac, Sambaar entendit ses sanglots. Lentement, il refit surface et s’approcha de la jeune fille.<br><br>
                
                Il se hissa à sa hauteur, plongeant son regard dans celui de Ndiémé. Elle releva la tête, les paupières embuées de larmes.<br><br>
                
                Le triton, avec une douceur inattendue, caressa son visage et entonna une mélodie envoûtante :
                
                Refrain :<br><br>
                
                Ndiémé, douce étoile au bord du lac,<br><br>
                Quand les nuages assombrissent ton doux regard,<br><br>
                Laisse la mer, avec ses vagues, t’envelopper,<br><br>
                À travers la nuit, une chanson d’espoir te chanter.<br><br>
                
                
                Touchée par la musique qui lui était dédiée, Ndiémé s’avança timidement vers Sambaar et se laissa envelopper dans ses bras.<br><br>
                
                Elle était désormais convaincue qu’il n’était pas une menace.
                
                </p>
            
            <div class="song-section">
                <div class="music-icon">🎵</div>
                <div class="song-title">La chanson de Ndiémé</div>
                <div class="lyrics">
                    <p>Ndiémé, Ndiémé, au bord du lac Naane,<br>
                    Où le doux murmure de l'eau chante,<br>
                    Mon cœur résonne au rythme de l'amour,<br>
                    Âme sœur, je t'attends chaque jour.</p>
                </div>
                
                <audio class="audio-player" controls>
                    <source src="Éternel Amour.mp3" type="audio/mpeg">
                    Votre navigateur ne supporte pas l'élément audio.
                </audio>
            </div>
        </div>

        <div class="chapter" id="chapter3">
            <h2 class="chapter-title">PARTIE III : Suite et fin</h2>
            <p>« T'es né de l'œuf d'Akara ? J'ai beaucoup entendu parler de cette légende populaire. Mais, au fait, qui t'a dit que je me prénomme Ndiémé ? » demanda-t-elle, intriguée. <br><br>« Oui, je suis le centième Sambaar. Quant à ton nom, en réalité, je ne le savais pas. Je me suis inspiré de Ndiémé, qui signifie “celle qui est aimée” ou “chérie”. » <br><br>

                « Hum… J’ignorais complètement cette signification de mon prénom. Si tu es un Sambaar, cela veut dire qu’Akara n’est pas une légende ? »<br><br>
                
                « Effectivement. J’en suis la preuve vivante. Et toi, de quelle race es-tu ? »<br><br>
                
                « Je suis une humaine. »<br><br>
                
                « Humaine ? C’est un concept nouveau pour moi. Ah oui ! Je viens à peine de naître, alors j’ai encore beaucoup à apprendre. »<br><br>
                
                « Comment ça, tu viens de naître ? »
                
                « L’œuf d’Akara me garde en son sein pendant ma formation. Il ne me libère que lorsque j’atteins la maturité, c’est-à-dire 18 ans. »<br><br>
                
                « … C’est curieux. Je n’avais pas remarqué ta barbe. » lança-t-elle, amusée.<br><br>
                
                Sambaar toucha son menton et découvrit une touffe de poils qui avait poussé. Sa barbe venait d’apparaître à l’instant même où il avait ressenti des papillons dans le ventre.<br><br>
                
                « Elle vient de se manifester. Peut-être est-ce une facette de moi que je dois découvrir. »<br><br>
                
                « Certainement ! Oh non ! Maman va me tuer ! Il faut que je file ! » s’écria Ndiémé en s’éloignant précipitamment.<br><br>
                
                « Attends, je vais laver tes vêtements pour toi. Ce n’est pas pour ça que tu pleurais ? » proposa le triton.<br><br>
                
                Ndiémé hocha la tête, et Sambaar plongea ses habits dans l’eau en un éclair. Lorsqu’il les ressortit, ils étaient comme neufs.<br><br>
                
                Pour le remercier, Ndiémé lui donna une bise sur la joue avant de s’éclipser. Sambaar, envoûté, resta un moment à rêvasser.<br><br><br>
                
                
                
                De retour dans les abysses, le triton alla trouver son amie Coraillie. Tout excité, il lui raconta sa rencontre avec l’humaine, leur discussion et les émotions qu’il avait ressenties.<br><br>
                
                Coraillie, captivée, lui expliqua certains mystères, notamment celui de sa barbe : <br><br>
                
                « Selon ce que j’ai compris des précédents Sambaars, leur barbe pousse uniquement lorsqu’ils tombent amoureux. »<br><br>
                
                « Cela signifie que… j’aime l’humaine ? Wow ! C’est si facile de tomber amoureux ? »<br><br>
                
                « Pas vraiment. Dans ton cas, on appelle ça un coup de foudre. Cette humaine est ton âme sœur. Tu dois gagner son cœur, sinon… tu mourras. »<br><br>
                
                Sambaar, abasourdi, s’écria : « Mourir ? Tu veux dire que je vais mourir si elle ne m’aime pas ? »<br><br>
                
                « Les tritons sont faits pour trouver leur âme sœur. Si ce n’est pas le cas ou si leur âme sœur les repousse, ils meurent inévitablement. C’est la règle. Aucun Sambaar n’y a échappé. »<br><br>
                
                « Ma vie dépend donc de son amour… »<br><br>
                
                « Pas d’inquiétude. Tu m’as dit qu’elle t’a donné une bise. Chez les humains, ce geste est souvent porteur d’espoir. Mais moi… Je suis amoureuse d’un humain qui serait sûrement horrifié par mon apparence. Il ne pourra jamais m’aimer. »<br><br>
                
                « Qui est-ce ? »<br><br>
                
                « Oublie ça. Tu ne le connais pas. »<br><br>
                
                « Ne te sous-estime pas, Coraillie. Tu es splendide. Il serait idiot de ne pas t’aimer à ta juste valeur. »<br><br>
                
                Coraillie, émue, répondit : « Merci pour le compliment, mais ça n’efface pas nos différences. Je suis une créature hybride, et lui… un terrien. »<br><br>
                
                « L’amour transcende les différences. Les plus belles choses naissent souvent des opposés. »<br><br>
                
                Inspiré, Sambaar composa une chanson dédiée à Coraillie, célébrant l’union entre deux mondes :<br><br>
                
                Refrain :  Coraillie, éclat de l’océan profond, votre amour résiste au temps, fécond,<br><br>
                Entre deux mondes, une harmonie s’esquisse,<br>
                Un futur radieux où votre amour luit.<br>
                
                Couplet 1 : D’un royaume sous-marin à la terre ferme, vos cœurs battent dans une même germe,<br><br>
                Les vagues murmurent un doux refrain,<br>
                Où l’amour transcende les frontières marines.<br><br>
                
                Refrain : Coraillie, éclat de l’océan profond, votre amour résiste au temps, fécond,<br><br>
                Entre deux mondes, une harmonie s’esquisse,<br>
                Un futur radieux où votre amour luit.<br><br>
                
                Couplet 2 : Comme les étoiles qui brillent au-dessus, vos rêves se tissent, en unissant vos vœux,<br><br>
                Laisse le temps guider vos destins croisés,<br>
                Vers un avenir où l’amour sera exalté.<br><br>
                
                Pont : Au-delà des abysses, au-delà des cieux, votre passion, unique, ne connaît pas de lieux,<br><br>
                Le monde humain peut être un océan nouveau,<br>
                Où votre amour deviendra un doux flambeau.<br><br>
                
                Refrain : Coraillie, éclat de l’océan profond, votre amour résiste au temps, fécond,<br><br>
                Entre deux mondes, une harmonie s’esquisse,<br>
                Un futur radieux où votre amour luit.<br><br>
                
                Couplet 3 :  lui , l’inconnu pour moi ,  l’élu de ton cœur véritable, Découvrira votre amour, irréfutable,<br><br>
                Laisse le destin tisser sa toile,<br>
                Dans l’écrin de vos rêves, sans égale..<br><br>
                
                Final : Coraillie, crois en votre destin commun, Les océans et les terres s’uniront en un,<br><br>
                Il  percevra votre harmonie,<br>
                Unissant vos cœurs dans une douce mélodie.<br><br>
                
            
                
                « Mille merci sambaar» s’émeut Coraillie. <br><br>
                
                « Soit ma force , je serai la sienne, bientôt l’amour illuminera nos vies »<br><br>
                
                « espérons le mon cher ami »<br><br>
                
                Les deux potes se câlinèrent profitant du réconfort qu’ils se transmettaient mutuellement. <br><br><br><br>
                
                
                
                
                
                
                
                Quelques jours plus tard, au lac Naane<br><br><br>
                
                Ndiémé et Sambaar approfondissaient leur lien, passant des heures à parler, chanter et rêver ensemble.<br><br>
                
                Mais un jour, Mbakhawou, le guetteur du village, la suivit discrètement. Lorsqu’il aperçut Sambaar, il s’exclama :<br><br>
                
                « Cette fille est folle ! Elle préfère un monstre aux hommes. Je vais alerter le village. »<br><br>
                
                Il battit le tam-tam d’alerte, rassemblant chasseurs, magiciens et villageois. Ils accoururent, armés et furieux.<br><br>
                
                Au lac, Mbakhawou désigna Sambaar. « Tuez-le ! Qu’attendez-vous ? »<br><br>
                
                « Non ! Ne lui faites pas de mal. Il est gentil ! » supplia Ndiémé en s’interposant.<br><br>
                
                « Écarte-toi ! Il t’a sûrement ensorcelée. Laisse-nous faire ! » gronda un chasseur.<br><br>
                
                « Si vous voulez le tuer, commencez par me tuer. Je ne bougerai pas. » Ndiémé, obstinée, refusa de céder.<br><br>
                
                Après un long silence, le roi intervint : « Si elle l’aime, qui sommes-nous pour nous opposer ? Rentrez chez vous. »<br><br>
                
                Tous obéirent, sauf Mbakhawou, qui s’insurgea : « Père, il l’a ensorcelée ! Nous ne pouvons pas abandonner. »<br><br>
                
                « Si tu veux rester ici, libre à toi. Nous, nous rentrons. » conclut le roi en s’éloignant avec ses hommes.<br><br>
                
                Mbakhawou, hystérique, invectiva longuement, mais ses paroles tombèrent dans l’oreille d’un sourd. Le couple au milieu du lac semblait même amusé par son spectacle ridicule.<br><br>
                
                Soudain, les eaux grondèrent mystérieusement, et le fils du roi se figea sur place.<br><br>
                Progressivement, une femme d’eau et de coraux, émergeant en soulevant des pans d’eau scintillants, fit son apparition.<br><br>
                
                « Mbakhawou, mon amour, mon cœur, te voilà enfin. Viens… viens dans mes bras, chéri », l’invita Coraillie d’une voix envoutante.<br><br>
                
                Pris d’une peur sans précédent, Mbakhawou grimpa à toute vitesse sur la branche la plus haute de l’arbre voisin.<br><br>
                
                « Au secours ! Au secours ! » criait-il désespérément.<br><br>
                
                Mais Coraillie, déterminée, fit pencher la branche qui le soutenait à l’aide de ses pouvoirs aquatiques. D’un craquement sinistre, elle la brisa.<br><br>
                
                « Aaaaaaah ! »<br><br>
                
                Sa chute dans les eaux du lac Naane fut aussi inévitable qu’effroyable, où sa prodigieuse dulcinée l’attendait patiemment.<br><br>
                
                Pendant ce temps, Ndiémé et Sambaar riaient à gorge déployée, trouvant la situation hilarante.<br><br>
                
                Rien, pas même la différence de leurs natures, ne pouvait vaincre leur amour intense.<br><br>
                Ndiémé, promettant une vie commune au triton, demanda la bénédiction de sa mère. Cette dernière, heureuse de ne pas avoir perdu sa fille chérie, accepta la relation avec Sambaar.<br><br>
                
                Déterminée, Ndiémé plongea dans les profondeurs du lac Naane pour retrouver son âme sœur. Leur premier baiser scella leur union, transformant la jeune femme en sirène, une moitié parfaitement unie à Sambaar, l’élu de son cœur pour l’éternité.<br><br>
                
                « C’est dans les eaux de l’amour véritable que les différences se dissolvent, formant une mélodie harmonieuse où chaque note contribue à la symphonie de la vie. »<br><br>
                
                FIN
                
                
                
                
                
                
                
                </p>
        </div>

        <div class="navigation">
            <button class="btn" id="prevBtn" disabled>Chapitre précédent</button>
            <button class="btn" id="nextBtn">Chapitre suivant</button>
        </div>
    </div>

    <script>
        const chapters = document.querySelectorAll('.chapter');
        const prevBtn = document.getElementById('prevBtn');
        const nextBtn = document.getElementById('nextBtn');
        const progressFill = document.getElementById('progress-fill');
        let currentChapter = 0;

        function updateChapters() {
            chapters.forEach((chapter, index) => {
                chapter.classList.remove('active');
                if (index === currentChapter) {
                    chapter.classList.add('active');
                }
            });

            prevBtn.disabled = currentChapter === 0;
            nextBtn.disabled = currentChapter === chapters.length - 1;

            // Update progress bar
            const progress = ((currentChapter + 1) / chapters.length) * 100;
            progressFill.style.width = `${progress}%`;

            // Pause any playing audio when changing chapters
            document.querySelectorAll('audio').forEach(audio => audio.pause());
        }

        prevBtn.addEventListener('click', () => {
            if (currentChapter > 0) {
                currentChapter--;
                updateChapters();
            }
        });

        nextBtn.addEventListener('click', () => {
            if (currentChapter < chapters.length - 1) {
                currentChapter++;
                updateChapters();
            }
        });

        // Initial update
        updateChapters();
    </script>
</body>
</html>
