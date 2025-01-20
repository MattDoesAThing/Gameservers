## Mission auto-start on server start 
* do not tick "autoinit" or set that flag
```
// MISSIONS CYCLE (see below)
class Missions {
   class Mission1 {
      template ="Antistasi_mapname.mapname";
      difficulty = "Regular"; //can be Recruit, Regular, Veteran or Custom. Custom needs setting up though.
      class Params {
         autoLoadLastGame = 60; //Automatically starts the mission 60 seconds after the first player connected to the server and no admin is logged in. {"No automatic load","1min","2min","3min","5min","10min"}
         LogLevel = 2; //Sets the log level during the setup. {"Error", "Info", "Debug", "Verbose"}
         A3A_logDebugConsole = 1; //Sets the Log debug console use during setup. {"None", "All non-dev", "All"}
      };
   };
};
```
"What are the file names for server hosting"

    Antistasi_abramia.abramia

    Antistasi_Altis.Altis

    Antistasi_blud_vidda.blud_vidda

    Antistasi_brf_sumava.brf_sumava

    Antistasi_cam_lao_nam.cam_lao_nam

    Antistasi_chernarus.chernarus

    Antistasi_chernarus_summer.chernarus_summer

    Antistasi_chernarus_winter.chernarus_winter

    Antistasi_cup_chernarus_A3.cup_chernarus_A3

    Antistasi_Enoch.Enoch

    Antistasi_Esseker.Esseker

    Antistasi_gm_weferlingen_summer.gm_weferlingen_summer

    Antistasi_gm_weferlingen_winter.gm_weferlingen_winter

    Antistasi_iron_excelsior_Tobruk.iron_excelsior_Tobruk

    Antistasi_Kapaulio.Kapaulio

    Antistasi_Kunduz.Kunduz

    Antistasi_lingor3.lingor3

    Antistasi_Lythium.Lythium

    Antistasi_Malden.Malden

    Antistasi_Napf.Napf

    Antistasi_NapfWinter.NapfWinter

    Antistasi_OPTRE_Madrigal.OPTRE_Madrigal

    Antistasi_Panthera3.Panthera3

    Antistasi_rhspkl.rhspkl

    Antistasi_ruha.ruha

    Antistasi_sara.sara

    Antistasi_SefrouRamal.SefrouRamal

    Antistasi_Sehreno.Sehreno

    Antistasi_SPE_Normandy.SPE_Normandy

    Antistasi_takistan.takistan

    Antistasi_Tanoa.Tanoa

    Antistasi_tem_anizay.tem_anizay

    Antistasi_Tembelan.Tembelan

    Antistasi_vn_khe_sanh.vn_khe_sanh

    Antistasi_vt7.vt7

    Antistasi_Winthera3.Winthera3

    Antistasi_green_sea.green_sea

    Antistasi_namalsk.namalsk

    Antistasi_spex_utah_beach.spex_utah_beach

    Antistasi_tem_kujari.tem_kujari

    Antistasi_UMB_Colombia.UMB_Colombia

    Antistasi_WW2_Omaha_Beach.WW2_Omaha_Beach

    Antistasi_pja310.pja310

    Antistasi_stozec.stozec

    Antistasi_yulakia.yulakia

    Antistasi_psyfx_pht.psyfx_pht

    Antistasi_Gulfcoast.Gulfcoast

    Antistasi_pulau.pulau

    Antistasi_mehland.mehland

    Antistasi_tem_chernarus.tem_chernarus

    Antistasi_tem_chernarusw.tem_chernarusw

    Antistasi_chernarusredux.chernarusredux

