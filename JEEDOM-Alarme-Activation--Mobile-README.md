---
layout: default
title: JEEDOM-Lampe
description: Explication widget Alarme-Activation (mobile)
---

# Widget "Alarme-Activation (mobile)" 

Widget pour Jeedom permettant d'afficher une icône pour une fonction de type <b>action ON/OFF</b>
<p><img src="Img/JEEDOM-Alarme-Activation-Resultat.png" alt="Resultat" /></p>
<blockquote>
    Le widget inclus d'office 12 types de lampes (6xON et 6xOFF). Il est possible d'ajouter ses propres icônes.
</blockquote>
<p><img src="Img/JEEDOM-Alarme.png" alt="Visuels" /></p>

<h1 id="Type de paramètre">Type de paramètre</h1>
<hr />
<h4 id="Logo">Choix de l'icône</h4>
Pour choisir le type de visuel à afficher, il faut ajouter les paramètres optionnels suivant :
<blockquote>
        <ul>
            <li><b>logoON-M</b> : Permet de choisir l'image pour la valeur ON<i>(valeur par défaut : alarm-status-T0-lock)</i></li>
            <li><b>logoON_type-M</b> : Permet de choisir l'extension pour l'image pour la valeur ON ou OFF <i>(valeur par défaut : png)</i></li>
            <li><b>logoOFF-M</b> : Permet de choisir l'image pour la valeur OFF<i>(valeur par défaut : alarm-status-T0-unlock)</i></li>
            <li><b>logoOFF_type-M</b> : Permet de choisir l'extension pour l'image pour la valeur ON ou OFF <i>(valeur par défaut : png)</i></li>
        </ul>
</blockquote>

<h4 id="TaIlle">Taille de l'image</h4>
Pour choisir la dimension de l'image il faut ajouter un paramètre optionnel<br/>
<blockquote>
        <ul>
            <li><b>sizeh-M</b> : Permet de choisir la hauteur de l'image <i>(valeur par défaut : 40)</i></li>
            <li><b>sizew-M</b> : Permet de choisir la largeur de l'image <i>(valeur par défaut : 40)</i></li>
        </ul>
</blockquote>

<h1 id="Aide Paramétrage">Aide pour le paramétrage du widget</h1>
<hr />
<h5 id="header-5">Paramétrage de l'équipement</h5>
<dl>
    <dd>Cliquez sur la roue crantée à gauche de la commande ON et/ou OFF</dd>
</dl>

<h5 id="header-5">Choix du widget et ajout des paramètres</h5>
<dl>
    <dd>Choisir le widget et ajouter les parametres voulus (Opération à faire sur la commande ON et OFF)</dd>
    <img src="Img/JEEDOM-Activation-Configuration.png" alt="Configuration"/>
</dl>
    
<h1 id="Add img">Ajout d'image</h1>
<hr />
<blockquote>
        Il est possible d'inclure d'autres icônes dans le widget.<br/>
        Le nommage des images n'est pas normalisé sur ce widget
</blockquote>

<hr />
<dl>
    <dt>Mise à jour JAG - 20190608</dt>
</dl>
<hr />
[back](./)