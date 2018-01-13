<Type Name="KeyValueStoreReplicaSettings" FullName="System.Fabric.KeyValueStoreReplicaSettings">
  <TypeSignature Language="C#" Value="public class KeyValueStoreReplicaSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeyValueStoreReplicaSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.KeyValueStoreReplicaSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class KeyValueStoreReplicaSettings" />
  <TypeSignature Language="F#" Value="type KeyValueStoreReplicaSettings = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            キー/値のストア レプリカの設定を表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyValueStoreReplicaSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplicaSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:System.Fabric.KeyValueStoreReplicaSettings" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableCopyNotificationPrefetch">
      <MemberSignature Language="C#" Value="public bool EnableCopyNotificationPrefetch { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableCopyNotificationPrefetch" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreReplicaSettings.EnableCopyNotificationPrefetch" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableCopyNotificationPrefetch As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableCopyNotificationPrefetch : bool with get, set" Usage="System.Fabric.KeyValueStoreReplicaSettings.EnableCopyNotificationPrefetch" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または開くときに、データベースをプリフェッチするかどうかを示す値を設定します。
            </summary>
        <value>
            有効な場合、false それ以外の場合は true を返します。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FullCopyMode">
      <MemberSignature Language="C#" Value="public System.Fabric.KeyValueStoreReplica.FullCopyMode FullCopyMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.KeyValueStoreReplica/FullCopyMode FullCopyMode" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreReplicaSettings.FullCopyMode" />
      <MemberSignature Language="VB.NET" Value="Public Property FullCopyMode As KeyValueStoreReplica.FullCopyMode" />
      <MemberSignature Language="F#" Value="member this.FullCopyMode : System.Fabric.KeyValueStoreReplica.FullCopyMode with get, set" Usage="System.Fabric.KeyValueStoreReplicaSettings.FullCopyMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreReplica+FullCopyMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはセカンダリ レプリカを作成するときに使用する完全なコピー モードを示す値を設定します。 <see cref="T:System.Fabric.KeyValueStoreReplica.FullCopyMode" /></summary>
        <value>
            完全なコピー モードを返します。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogTruncationIntervalInMinutes">
      <MemberSignature Language="C#" Value="public int LogTruncationIntervalInMinutes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 LogTruncationIntervalInMinutes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreReplicaSettings.LogTruncationIntervalInMinutes" />
      <MemberSignature Language="VB.NET" Value="Public Property LogTruncationIntervalInMinutes As Integer" />
      <MemberSignature Language="F#" Value="member this.LogTruncationIntervalInMinutes : int with get, set" Usage="System.Fabric.KeyValueStoreReplicaSettings.LogTruncationIntervalInMinutes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            その後の間隔の設定を取得または<see cref="T:System.Fabric.KeyValueStoreReplica" />ローカル ストアがある場合、ローカルの切り捨てを行うための試行がログを格納<see cref="P:System.Fabric.LocalEseStoreSettings.EnableIncrementalBackup" />有効になっているし、バックアップが開始されていませんユーザーがこの間隔中にします。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryNotificationMode">
      <MemberSignature Language="C#" Value="public System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode SecondaryNotificationMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.KeyValueStoreReplica/SecondaryNotificationMode SecondaryNotificationMode" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreReplicaSettings.SecondaryNotificationMode" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondaryNotificationMode As KeyValueStoreReplica.SecondaryNotificationMode" />
      <MemberSignature Language="F#" Value="member this.SecondaryNotificationMode : System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode with get, set" Usage="System.Fabric.KeyValueStoreReplicaSettings.SecondaryNotificationMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreReplica+SecondaryNotificationMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または有効にするセカンダリ通知モードを示す値を設定します。 <see cref="T:System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode" /></summary>
        <value>
            セカンダリ通知モードを返します。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransactionDrainTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan TransactionDrainTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan TransactionDrainTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreReplicaSettings.TransactionDrainTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property TransactionDrainTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.TransactionDrainTimeout : TimeSpan with get, set" Usage="System.Fabric.KeyValueStoreReplicaSettings.TransactionDrainTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または未解決のトランザクションをホスト プロセスを強制的に終了する前にプライマリ ロールから降格中にドレインを実行する必要がある時間を示す値を設定します。
            </summary>
        <value>
            ドレイン タイムアウト値を返します。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>