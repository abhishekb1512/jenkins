pipeline {
  agent any
  stages {
    stage('Fetch Dates') {
      steps {
        sh '. ~/.bash_profile;sqlplus -S <username>/<password>@<sid>@/root/test.sql prev_cutoff_date'
      }
    }

    stage('Batch 1') {
      parallel {
        stage('I_101 - SQUSA') {
          steps {
            echo 'Testing..'
          }
        }

        stage('1.34 - POST') {
          steps {
            sh 'echo "1.34"'
          }
        }

        stage('I_241') {
          steps {
            sh 'echo "I_241"'
          }
        }

        stage('1.17.1') {
          steps {
            sh 'echo "1.1.17"'
          }
        }

        stage('1.22 - Clienti bundle IPTV') {
          steps {
            sh 'echo "1.22"'
          }
        }

        stage('1.22 - Annuali - POST') {
          steps {
            sh 'echo "1.22 - Annuali - POST"'
          }
        }

        stage('1.8 - MultiDiscount') {
          steps {
            sh 'echo "1.8 - MultiDiscount"'
          }
        }

        stage('1.8 - DiscDiration') {
          steps {
            sh 'echo "1.8 - DiscDiration"'
          }
        }

        stage('1.36 - POST') {
          steps {
            sh 'echo "1.36 - POST"'
          }
        }

      }
    }

    stage('Batch 2') {
      parallel {
        stage('Batch 2') {
          steps {
            echo 'batch 2'
          }
        }

        stage('1.11 - POST') {
          steps {
            sh 'echo "1.11 - POST"'
          }
        }

        stage('6.5 - POST') {
          steps {
            sh 'echo "6.5 - POST"'
          }
        }

        stage('WP_SCONTI_1') {
          steps {
            sh 'echo "WP_SCONTI_1"'
          }
        }

        stage('5.75.2 ') {
          steps {
            sh 'echo "5.75.2"'
          }
        }

        stage('6.2 - POST') {
          steps {
            sh 'echo "6.2 - POST"'
          }
        }

        stage('5.24') {
          steps {
            sh 'echo "5.24"'
          }
        }

      }
    }

    stage('Batch 3') {
      parallel {
        stage(' I_105') {
          steps {
            echo 'batch 3 '
            sh 'echo "I_105"'
          }
        }

        stage('I_201') {
          steps {
            sh 'echo "I_201"'
          }
        }

        stage('WP RC') {
          steps {
            sh 'echo "WP RC"'
          }
        }

        stage('I_208_G') {
          steps {
            sh 'echo "I_208_G"'
          }
        }

        stage('2.11 - POST') {
          steps {
            sh 'echo "2.11 - POST"'
          }
        }

      }
    }

    stage('Batch 4') {
      parallel {
        stage('1.17') {
          steps {
            sh 'echo "1.17"'
          }
        }

        stage('WP_BonificaEventuali') {
          steps {
            sh 'echo "WP_BonificaEventualiVociNonSospeseCessatiClever"'
          }
        }

        stage('I_210 (PPV Definitiva PRE)') {
          steps {
            sh 'echo "I_210 (PPV Definitiva PRE)"'
          }
        }

        stage('6.2.1 - POST') {
          steps {
            sh 'echo "6.2.1 - POST"'
          }
        }

        stage('1.27 - POST') {
          steps {
            sh 'echo "1.27 - POST"'
          }
        }

        stage('1.8.4') {
          steps {
            sh 'echo "1.8.4"'
          }
        }

        stage('1.8.6') {
          steps {
            sh 'echo "1.8.6"'
          }
        }

      }
    }

    stage('Batch 5') {
      parallel {
        stage('0.11 WP NRC') {
          steps {
            sh 'echo "0.11 WP NRC"'
          }
        }

        stage('Unsuppress_IPTV') {
          steps {
            sh 'echo "Unsuppress_IPTV"'
          }
        }

        stage('Estrazione_Clienti_Bundle') {
          steps {
            sh 'echo "Estrazione_Clienti_Bundle"'
          }
        }

        stage('1.8.1 - DiscOnNRC') {
          steps {
            sh 'echo "1.8.1 - DiscOnNRC"'
          }
        }

        stage('5.76.3') {
          steps {
            sh 'echo "5.76.3"'
          }
        }

        stage('1.8.1 - DiscOnRC') {
          steps {
            sh 'echo "1.8.1 - DiscOnRC"'
          }
        }

        stage('I_112 (Bonifica Referente FX)') {
          steps {
            sh 'echo "I_112 (Bonifica Referente FX)"'
          }
        }

        stage('5.76.1') {
          steps {
            sh 'echo "5.76.1"'
          }
        }

        stage('2.7') {
          steps {
            sh 'echo "2.7"'
          }
        }

      }
    }

    stage('Batch 6') {
      parallel {
        stage('WP_SCONTI_2') {
          steps {
            sh 'echo "WP_SCONTI_2"'
          }
        }

        stage('2.12.2/5.76.2(5.76)') {
          steps {
            sh 'echo "2.12.2/5.76.2(5.76)"'
          }
        }

        stage('ControlloCaratteriSporchiFW') {
          steps {
            sh 'echo "ControlloCaratteriSporchiFW"'
          }
        }

        stage('I_208_C') {
          steps {
            sh 'echo "I_208_C"'
          }
        }

        stage('STORNI_NON_AUTOMATICI') {
          steps {
            sh 'echo "STORNI_NON_AUTOMATICI"'
          }
        }

        stage('2.12.1') {
          steps {
            sh 'echo "2.12.1"'
          }
        }

        stage('0.7.2') {
          steps {
            sh 'echo "0.7.2"'
          }
        }

        stage('I_208_F') {
          steps {
            sh 'echo "I_208_F"'
          }
        }

      }
    }

    stage('Batch 7 ') {
      parallel {
        stage('I_007') {
          steps {
            sh 'echo "I_007"'
          }
        }

        stage('I_204') {
          steps {
            sh 'echo "I_204"'
          }
        }

        stage('I_208_L') {
          steps {
            sh 'echo "I_208_L"'
          }
        }

        stage('9.6 Pa - Incongruenze') {
          steps {
            sh 'echo "9.6 Pa - Incongruenze"'
          }
        }

        stage('0.7') {
          steps {
            sh 'echo "0.7"'
          }
        }

        stage('9.6 Split payment (ADJ no PA)') {
          steps {
            sh 'echo "9.6 Split payment (ADJ no PA)"'
          }
        }

        stage('2.1.2') {
          steps {
            sh 'echo "2.1.2 Do not run SF cleanup"'
          }
        }

        stage('2.8.1') {
          steps {
            sh 'echo "2.8.1"'
          }
        }

        stage('WP_Coerenza_Consistenza') {
          steps {
            sh 'echo "WP_Coerenza_Consistenza"'
          }
        }

      }
    }

    stage('Batch 8 ') {
      parallel {
        stage('I_009 ') {
          steps {
            sh 'echo "I_009"'
          }
        }

        stage('Doppie Penali') {
          steps {
            sh 'echo "Doppie Penali"'
          }
        }

        stage('I_208_E') {
          steps {
            sh 'echo "I_208_E"'
          }
        }

        stage('I_203') {
          steps {
            sh 'echo "I_203"'
          }
        }

        stage('2.12.3') {
          steps {
            sh 'echo "2.12.3"'
          }
        }

      }
    }

    stage('Batch 9') {
      parallel {
        stage('I_237 Quadr_Formato_Elettronico') {
          steps {
            sh 'echo "I_237 Quadr_Formato_Elettronico - POST"'
          }
        }

        stage('SPLIT_PAYMENT V1') {
          steps {
            sh 'echo "SPLIT_PAYMENT V1"'
          }
        }

        stage('Report Contributi TV da fatturare') {
          steps {
            sh 'echo "Report Contributi TV da fatturare"'
          }
        }

      }
    }

    stage('Finish') {
      steps {
        echo 'Finish'
      }
    }

  }
}