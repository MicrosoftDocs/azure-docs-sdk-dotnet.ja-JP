<Type Name="IMigrationOperations" FullName="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations">
  <TypeSignature Language="C#" Value="public interface IMigrationOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMigrationOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMigrationOperations" />
  <TypeSignature Language="F#" Value="type IMigrationOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            レガシ アプライアンスの移行
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginUpdateDataContainerMigrationStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginUpdateDataContainerMigrationStatusAsync (string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginUpdateDataContainerMigrationStatusAsync(string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.BeginUpdateDataContainerMigrationStatusAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginUpdateDataContainerMigrationStatusAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="iMigrationOperations.BeginUpdateDataContainerMigrationStatusAsync (configId, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="configId">
            サービスへの構成のインポート中に指定された構成の一意の識別子
            </param>
        <param name="customRequestHeaders">
            カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            更新プログラム データ コンテナー statusThe rest api は、指定された構成ですべてのボリューム コンテナーのサービスを提供するターゲット デバイスからのボリューム コンテナーの移行の状態を更新ヒュドラ仕様
            </summary>
        <returns>
            これは、非同期呼び出しは、すべてのタスク応答
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateMigrationConfirmStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginUpdateMigrationConfirmStatusAsync (string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginUpdateMigrationConfirmStatusAsync(string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.BeginUpdateMigrationConfirmStatusAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginUpdateMigrationConfirmStatusAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="iMigrationOperations.BeginUpdateMigrationConfirmStatusAsync (configId, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="configId">
            サービスへの構成のインポート中に指定された構成の一意の識別子
            </param>
        <param name="customRequestHeaders">
            カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された構成でターゲット アプライアンスからすべてのデータ コンテナーのサービスへの確認 (コミットまたはロールバック) 状態を api の更新プログラム rest の更新プログラムの確認移行 statusThe ヒュドラ仕様
            </summary>
        <returns>
            これは、非同期呼び出しは、すべてのタスク応答
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateMigrationPlanAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginUpdateMigrationPlanAsync (string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginUpdateMigrationPlanAsync(string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.BeginUpdateMigrationPlanAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginUpdateMigrationPlanAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="iMigrationOperations.BeginUpdateMigrationPlanAsync (configId, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="configId">
            サービスへの構成のインポート中に指定された構成の一意の識別子
            </param>
        <param name="customRequestHeaders">
            カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ヒュドラ spec の更新プログラムの移行計画 rest apiThe rest api は、指定された構成ですべてのボリューム コンテナーのサービスを提供するターゲット アプライアンスから移行計画を更新します。
            </summary>
        <returns>
            これは、非同期呼び出しは、すべてのタスク応答
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfirmMigrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt; ConfirmMigrationAsync (string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest confirmMigrationRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt; ConfirmMigrationAsync(string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest confirmMigrationRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.ConfirmMigrationAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ConfirmMigrationAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt;" Usage="iMigrationOperations.ConfirmMigrationAsync (configId, confirmMigrationRequest, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="confirmMigrationRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="configId">
            サービスへの構成のインポート中に指定された構成の一意の識別子
            </param>
        <param name="confirmMigrationRequest">
            確認の移行要求は、ボリューム コンテナーとロールバック/コミット操作を実行するの一覧を指定します。
            </param>
        <param name="customRequestHeaders">
            カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ヒュドラ仕様確認移行 rest apiThe rest api は、コミットまたはロールバックの指定された構成ですべてのデータ コンテナーの移行後のデータ コンテナーのことを確認
            </summary>
        <returns>
            移行ジョブの状態の応答モデル。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAllMigrationPlanAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList&gt; GetAllMigrationPlanAsync (Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList&gt; GetAllMigrationPlanAsync(class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.GetAllMigrationPlanAsync(Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAllMigrationPlanAsync : Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList&gt;" Usage="iMigrationOperations.GetAllMigrationPlanAsync (customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customRequestHeaders">
            カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ヒュドラ仕様のすべての移行 rest apiThe rest api が選択されている storsimple のリソースに対するインポート構成をすべての構成 id を返しますの取得します。
            </summary>
        <returns>
            Get 移行計画の応答本文は rest api です。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDataContainerMigrationStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatusList&gt; GetDataContainerMigrationStatusAsync (string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatusList&gt; GetDataContainerMigrationStatusAsync(string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.GetDataContainerMigrationStatusAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDataContainerMigrationStatusAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatusList&gt;" Usage="iMigrationOperations.GetDataContainerMigrationStatusAsync (configId, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatusList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="configId">
            サービスへの構成のインポート中に指定された構成の一意の識別子
            </param>
        <param name="customRequestHeaders">
            カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された構成ですべてのボリューム コンテナーのサービスからのボリューム コンテナーの移行状態の状態を api を返します。 rest の Get データ コンテナー移行 statusThe ヒュドラ仕様
            </summary>
        <returns>
            応答本文は、データ コンテナーの移行状態を取得します。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMigrationConfirmStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatus&gt; GetMigrationConfirmStatusAsync (string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatus&gt; GetMigrationConfirmStatusAsync(string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.GetMigrationConfirmStatusAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetMigrationConfirmStatusAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatus&gt;" Usage="iMigrationOperations.GetMigrationConfirmStatusAsync (configId, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="configId">
            サービスへの構成のインポート中に指定された構成の一意の識別子
            </param>
        <param name="customRequestHeaders">
            カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された構成ですべてのボリューム コンテナーのサービスからの確認 (コミットまたはロールバック) 状態を api rest get 確認移行ステータス rest apiThe のヒュドラ仕様
            </summary>
        <returns>
            応答本文の移行の状態を確認する rest api です。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMigrationPlanAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList&gt; GetMigrationPlanAsync (string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList&gt; GetMigrationPlanAsync(string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.GetMigrationPlanAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetMigrationPlanAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList&gt;" Usage="iMigrationOperations.GetMigrationPlanAsync (configId, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="configId">
            サービスへの構成のインポート中に指定された構成の一意の識別子
            </param>
        <param name="customRequestHeaders">
            カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Get 移行プランのヒュドラ仕様 rest api get が指定された構成ですべてのボリューム コンテナーのサービスから、移行の計画
            </summary>
        <returns>
            Get 移行計画の応答本文は rest api です。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportLegacyApplianceConfigAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; ImportLegacyApplianceConfigAsync (string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig request, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; ImportLegacyApplianceConfigAsync(string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig request, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.ImportLegacyApplianceConfigAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ImportLegacyApplianceConfigAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iMigrationOperations.ImportLegacyApplianceConfigAsync (configId, request, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="request" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="configId">
            インポートされている構成の一意の id
            </param>
        <param name="request">
            レガシ アプライアンス構成をインポートします。
            </param>
        <param name="customRequestHeaders">
            カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            レガシ アプライアンスの構成でインポート ヒュドラ仕様は rest api です。Rest api サービスのレガシの構成のインポート
            </summary>
        <returns>
            HTTP ステータス コードと要求 ID を含む標準サービスの応答
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MigrationImportDataContainerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt; MigrationImportDataContainerAsync (string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationImportDataContainerRequest importDCRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt; MigrationImportDataContainerAsync(string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationImportDataContainerRequest importDCRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.MigrationImportDataContainerAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationImportDataContainerRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member MigrationImportDataContainerAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationImportDataContainerRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt;" Usage="iMigrationOperations.MigrationImportDataContainerAsync (configId, importDCRequest, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="importDCRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationImportDataContainerRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="configId">
            サービスへの構成のインポート中に指定された構成の一意の識別子
            </param>
        <param name="importDCRequest">
            インポート データ コンテナーからの要求を移行するデータ コンテナーの一覧を指定します。
            </param>
        <param name="customRequestHeaders">
            カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定した設定ですべて/固有のデータ コンテナーのボリューム コンテナーの移行を api 開始 rest のインポート データ コンテナー rest apiThe ヒュドラ仕様
            </summary>
        <returns>
            移行ジョブの状態の応答モデル。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartMigrationPlanAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt; StartMigrationPlanAsync (Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest startPlanRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt; StartMigrationPlanAsync(class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest startPlanRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.StartMigrationPlanAsync(Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StartMigrationPlanAsync : Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt;" Usage="iMigrationOperations.StartMigrationPlanAsync (startPlanRequest, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="startPlanRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="startPlanRequest">
            移行計画の要求モデルを開始します。 オブジェクトは、移行を予定を計算する必要があるボリューム コンテナーの一覧を渡します。
            </param>
        <param name="customRequestHeaders">
            カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            移行計画の開始のヒュドラ仕様 rest APIThe rest api で指定した設定ですべて/特定のボリューム コンテナーの移行にかかった時間の推定値の開始
            </summary>
        <returns>
            移行ジョブの状態の応答モデル。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDataContainerMigrationStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateDataContainerMigrationStatusAsync (string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateDataContainerMigrationStatusAsync(string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.UpdateDataContainerMigrationStatusAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateDataContainerMigrationStatusAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="iMigrationOperations.UpdateDataContainerMigrationStatusAsync (configId, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="configId">
            configId
            </param>
        <param name="customRequestHeaders">
            カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>To be added.</summary>
        <returns>
            非同期タスクに関する情報
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMigrationConfirmStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateMigrationConfirmStatusAsync (string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateMigrationConfirmStatusAsync(string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.UpdateMigrationConfirmStatusAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateMigrationConfirmStatusAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="iMigrationOperations.UpdateMigrationConfirmStatusAsync (configId, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="configId">
            移行のレガシの構成 id のステータスを更新する必要があることを確認
            </param>
        <param name="customRequestHeaders">
            カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>To be added.</summary>
        <returns>
            非同期タスクに関する情報
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMigrationPlanAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateMigrationPlanAsync (string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateMigrationPlanAsync(string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.UpdateMigrationPlanAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateMigrationPlanAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="iMigrationOperations.UpdateMigrationPlanAsync (configId, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="configId">
            configId
            </param>
        <param name="customRequestHeaders">
            カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>To be added.</summary>
        <returns>
            非同期タスクに関する情報
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>