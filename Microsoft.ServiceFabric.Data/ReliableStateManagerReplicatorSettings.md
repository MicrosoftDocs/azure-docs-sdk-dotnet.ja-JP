<Type Name="ReliableStateManagerReplicatorSettings" FullName="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings">
  <TypeSignature Language="C#" Value="public class ReliableStateManagerReplicatorSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ReliableStateManagerReplicatorSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class ReliableStateManagerReplicatorSettings" />
  <TypeSignature Language="F#" Value="type ReliableStateManagerReplicatorSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            レプリケーターの構成設定
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReliableStateManagerReplicatorSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BatchAcknowledgementInterval">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; BatchAcknowledgementInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; BatchAcknowledgementInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.BatchAcknowledgementInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property BatchAcknowledgementInterval As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.BatchAcknowledgementInterval : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.BatchAcknowledgementInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または受信確認を送信する前に、操作を受信した後、レプリケーターが待機する時間を設定します。
            既定値は、5 ミリ秒です。
            </summary>
        <value>受信確認のバッチの間隔。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckpointThresholdInMB">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; CheckpointThresholdInMB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; CheckpointThresholdInMB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.CheckpointThresholdInMB" />
      <MemberSignature Language="VB.NET" Value="Public Property CheckpointThresholdInMB As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.CheckpointThresholdInMB : Nullable&lt;int&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.CheckpointThresholdInMB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはチェックポイントしきい値を設定します。 ログの使用量がこの値を超えると、チェックポイントが開始されます。
            既定値は 50 です。
            単位は MB です。
            </summary>
        <value>チェックポイントしきい値です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="reliableStateManagerReplicatorSettings.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj">
            チェックするオブジェクト。
            </param>
        <summary>
            指定した ReplicatorSettings が現在のオブジェクトと等しいかどうかを判断します。
            </summary>
        <returns>
            <see cref="T:System.Boolean" />。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="reliableStateManagerReplicatorSettings.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            この型のハッシュ関数として機能します。
            </summary>
        <returns>
            <see cref="T:System.Int32" />ハッシュ コードを表すです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitialCopyQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; InitialCopyQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; InitialCopyQueueSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.InitialCopyQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property InitialCopyQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.InitialCopyQueueSize : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.InitialCopyQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはコピー操作を含むレプリケーターの内部コピー操作キューの初期サイズを設定します。
            既定値は 64 です。
            値は、コピー操作キューの操作の数です。 2 のべき乗でなければなりません。
            </summary>
        <value>初期コピー キューのサイズ。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitialPrimaryReplicationQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; InitialPrimaryReplicationQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; InitialPrimaryReplicationQueueSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.InitialPrimaryReplicationQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property InitialPrimaryReplicationQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.InitialPrimaryReplicationQueueSize : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.InitialPrimaryReplicationQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、初期プライマリ レプリケーション キューのサイズを設定します。
            既定値は 64 です。
            値は、プライマリ レプリケーション キュー内の操作の数です。 2 のべき乗でなければなりません。
            </summary>
        <value>初期プライマリ レプリケーション キューのサイズ。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitialSecondaryReplicationQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; InitialSecondaryReplicationQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; InitialSecondaryReplicationQueueSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.InitialSecondaryReplicationQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property InitialSecondaryReplicationQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.InitialSecondaryReplicationQueueSize : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.InitialSecondaryReplicationQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはセカンダリの最初のレプリケーション キューのサイズを設定します。
            既定値は 64 です。
            値は、セカンダリのレプリケーション キュー内の操作の数です。 2 のべき乗でなければなりません。
            </summary>
        <value>初期セカンダリのレプリケーション キューのサイズ。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxAccumulatedBackupLogSizeInMB">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxAccumulatedBackupLogSizeInMB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxAccumulatedBackupLogSizeInMB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxAccumulatedBackupLogSizeInMB" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxAccumulatedBackupLogSizeInMB As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxAccumulatedBackupLogSizeInMB : Nullable&lt;int&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxAccumulatedBackupLogSizeInMB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバックアップ全体にわたって累積バックアップ ログの最大サイズを設定します。 要求によって生成されたログをバックアップ MaxAccumulatedBackupLogSizeInMB よりも大きい値を指定する最後の完全バックアップを含む蓄積されたログの合計サイズが発生した場合、増分バックアップ要求は失敗します。
            そのような場合には、ユーザーは完全バックアップを取得する必要があります。
            既定値は、800 です。
            単位は MB です。
            </summary>
        <value>最大数は、バックアップ ログ サイズ (mb) を蓄積します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxCopyQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxCopyQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxCopyQueueSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxCopyQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxCopyQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxCopyQueueSize : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxCopyQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはコピー操作を含む複製物作成会社の内部コピー操作キューの最大サイズを設定します。
            既定値は 1024 です。
            値は、コピー操作キューの操作の最大数です。 2 のべき乗でなければなりません。
            </summary>
        <value>コピーの最大キュー サイズです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxMetadataSizeInKB">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxMetadataSizeInKB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxMetadataSizeInKB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxMetadataSizeInKB" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxMetadataSizeInKB As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxMetadataSizeInKB : Nullable&lt;int&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxMetadataSizeInKB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはこのレプリカに関連付けられているレプリケーター キロバイト単位で指定するときに、余分な永続的な記憶域の容量を予約済み設定します。 この値は、4 の倍数である必要があります。
            既定値は 4 ですが、 単位は KB です。
            </summary>
        <value>メタデータの最大サイズ。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPrimaryReplicationQueueMemorySize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxPrimaryReplicationQueueMemorySize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxPrimaryReplicationQueueMemorySize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxPrimaryReplicationQueueMemorySize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPrimaryReplicationQueueMemorySize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxPrimaryReplicationQueueMemorySize : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxPrimaryReplicationQueueMemorySize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または最大のプライマリ レプリケーション キューのメモリ サイズを設定します。
            既定値は、0 で、メモリの制限がないことを意味します。
            単位はバイトです。
            </summary>
        <value>最大のプライマリ レプリケーション キューのメモリ サイズ。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPrimaryReplicationQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxPrimaryReplicationQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxPrimaryReplicationQueueSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxPrimaryReplicationQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPrimaryReplicationQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxPrimaryReplicationQueueSize : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxPrimaryReplicationQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または最大のプライマリ レプリケーション キューのサイズを設定します。
            既定値は 1024 です。
            値は、プライマリ レプリケーション キュー内の操作の最大数です。 2 のべき乗でなければなりません。
            </summary>
        <value>最大のプライマリ レプリケーション キューのサイズ。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxRecordSizeInKB">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxRecordSizeInKB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxRecordSizeInKB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxRecordSizeInKB" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxRecordSizeInKB As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxRecordSizeInKB : Nullable&lt;int&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxRecordSizeInKB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはレプリケーターがこのレプリカに関連付けられているログ用に指定されたキロバイトを書き込むことが最大レコード サイズを設定します。 この値は 4 と以上 128 までの倍数である必要があります。
            既定値は 1024 です。 単位は KB です。
            </summary>
        <value>最大レコード サイズ。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxReplicationMessageSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxReplicationMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxReplicationMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxReplicationMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReplicationMessageSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxReplicationMessageSize : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxReplicationMessageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはレプリケーションの最大メッセージ サイズを設定します。
            既定値は、50 MB です。
            単位はバイトです。
            </summary>
        <value>レプリケーションの最大メッセージ サイズ。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSecondaryReplicationQueueMemorySize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxSecondaryReplicationQueueMemorySize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxSecondaryReplicationQueueMemorySize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxSecondaryReplicationQueueMemorySize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxSecondaryReplicationQueueMemorySize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxSecondaryReplicationQueueMemorySize : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxSecondaryReplicationQueueMemorySize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または max セカンダリのレプリケーション キューのメモリ サイズを設定します。
            既定値は、0 で、メモリの制限がないことを意味します。
            単位はバイトです。
            </summary>
        <value>最大のセカンダリ レプリケーション キューのサイズ。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSecondaryReplicationQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxSecondaryReplicationQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxSecondaryReplicationQueueSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxSecondaryReplicationQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxSecondaryReplicationQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxSecondaryReplicationQueueSize : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxSecondaryReplicationQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または max セカンダリのレプリケーション キューのサイズを設定します。
            既定値は 2048 です。
            値は、セカンダリのレプリケーション キュー内の操作の最大数です。 2 のべき乗でなければなりません。
            </summary>
        <value>最大のセカンダリ レプリケーション キューのサイズ。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxStreamSizeInMB">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxStreamSizeInMB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxStreamSizeInMB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxStreamSizeInMB" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxStreamSizeInMB As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxStreamSizeInMB : Nullable&lt;int&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxStreamSizeInMB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            非推奨
            </summary>
        <value>ストリームの最大サイズ。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxWriteQueueDepthInKB">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxWriteQueueDepthInKB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxWriteQueueDepthInKB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxWriteQueueDepthInKB" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxWriteQueueDepthInKB As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxWriteQueueDepthInKB : Nullable&lt;int&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MaxWriteQueueDepthInKB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはコア ロガーは、このレプリカに関連付けられているログのキロバイト単位で指定として使用できる最大の書き込みキューの深さを設定します。 この値は、コア ロガーの更新時に未処理になる可能性がある最大バイト数です。 0 の場合、コア ロガーは適切な値または 4 の倍数を計算します。
            既定値は 0 です。
            単位は KB です。
            </summary>
        <value>最大数は、キューの深さを記述します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinLogSizeInMB">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MinLogSizeInMB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MinLogSizeInMB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MinLogSizeInMB" />
      <MemberSignature Language="VB.NET" Value="Public Property MinLogSizeInMB As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MinLogSizeInMB : Nullable&lt;int&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.MinLogSizeInMB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または最小のログのサイズを設定します。 この値以下に、ログのサイズ削減する場合、切り捨ては開始されません。
            既定値は 0 です。
            </summary>
        <value>最小のログのサイズ。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OptimizeForLocalSSD">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; OptimizeForLocalSSD { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; OptimizeForLocalSSD" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.OptimizeForLocalSSD" />
      <MemberSignature Language="VB.NET" Value="Public Property OptimizeForLocalSSD As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.OptimizeForLocalSSD : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.OptimizeForLocalSSD" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            非推奨
            </summary>
        <value>場合は、OptimizeForLocalSSD オプションが有効になっているとします。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OptimizeLogForLowerDiskUsage">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; OptimizeLogForLowerDiskUsage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; OptimizeLogForLowerDiskUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.OptimizeLogForLowerDiskUsage" />
      <MemberSignature Language="VB.NET" Value="Public Property OptimizeLogForLowerDiskUsage As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.OptimizeLogForLowerDiskUsage : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.OptimizeLogForLowerDiskUsage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または true の場合、ログが、ログ IO パフォーマンスが低下の少ないディスク領域が使用されている方法でを最適化するときに、フラグを設定します。 False の場合、ログはディスク容量を使用してが IO のパフォーマンスが向上します。
            既定値は true です。
            </summary>
        <value>場合は、OptimizeLogForLowerDiskUsage オプションが有効になっているとします。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicatorAddress">
      <MemberSignature Language="C#" Value="public string ReplicatorAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplicatorAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.ReplicatorAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplicatorAddress As String" />
      <MemberSignature Language="F#" Value="member this.ReplicatorAddress : string with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.ReplicatorAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または {ip} 内のアドレスの設定: この複製物作成会社が他の複製物作成会社と通信するときに使用する {port} 形式です。
            既定値は、"localhost:0"は、実行時に動的なポート番号を取得します。
            レプリケーターがコンテナーの内部実行されている場合は、セットアップをやり直す必要があります<see cref="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.ReplicatorListenAddress" />と<see cref="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.ReplicatorPublishAddress" />です。
            </summary>
        <value>レプリケーターのアドレス。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicatorListenAddress">
      <MemberSignature Language="C#" Value="public string ReplicatorListenAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplicatorListenAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.ReplicatorListenAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplicatorListenAddress As String" />
      <MemberSignature Language="F#" Value="member this.ReplicatorListenAddress : string with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.ReplicatorListenAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または {ip} 内のアドレスの設定: この複製物作成会社が他の複製物作成会社から情報を受信に使用する {port} 形式です。
            既定値は、"localhost:0"は、実行時に動的なポート番号を取得します。
            リッスン アドレスの一部で {ip} から取得できる<see cref="P:System.Fabric.CodePackageActivationContext.ServiceListenAddress" />です。
            </summary>
        <value>レプリケーターのアドレス。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicatorPublishAddress">
      <MemberSignature Language="C#" Value="public string ReplicatorPublishAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplicatorPublishAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.ReplicatorPublishAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplicatorPublishAddress As String" />
      <MemberSignature Language="F#" Value="member this.ReplicatorPublishAddress : string with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.ReplicatorPublishAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または {ip} で、アドレスを設定します。 この複製物作成会社が他の複製物作成会社に情報を送信に使用する {port} 形式です。
            既定値は、"localhost:0"は、実行時に動的なポート番号を取得します。
            パブリッシュ アドレスの一部で {ip} から取得できる<see cref="P:System.Fabric.CodePackageActivationContext.ServicePublishAddress" />です。
            </summary>
        <value>レプリケーターのアドレス。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryInterval">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; RetryInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; RetryInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.RetryInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryInterval As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.RetryInterval : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.RetryInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはレプリケーターがプライマリからのメッセージを受信したことを確認するセカンダリ セカンダリへのメッセージを送信した後に待機する時間を設定します。
            既定値は、5 秒です。
            </summary>
        <value>再試行の間隔。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryClearAcknowledgedOperations">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; SecondaryClearAcknowledgedOperations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; SecondaryClearAcknowledgedOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.SecondaryClearAcknowledgedOperations" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondaryClearAcknowledgedOperations As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.SecondaryClearAcknowledgedOperations : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.SecondaryClearAcknowledgedOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定フラグを true にセカンダリのレプリケーターはプライマリに操作の受信確認の後に、インメモリ キューをクリアする必要があります (操作がフラッシュされた後にディスクに)。
            既定値は false です。
            設定、これを"TRUE"になります、フェールオーバー後にレプリカをキャッチしながら、新しいプライマリでは、追加のディスク読み取り。
            </summary>
        <value>場合は、SecondaryClearAcknowledgedOperations オプションが有効になっているとします。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecurityCredentials">
      <MemberSignature Language="C#" Value="public System.Fabric.SecurityCredentials SecurityCredentials { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.SecurityCredentials SecurityCredentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.SecurityCredentials" />
      <MemberSignature Language="VB.NET" Value="Public Property SecurityCredentials As SecurityCredentials" />
      <MemberSignature Language="F#" Value="member this.SecurityCredentials : System.Fabric.SecurityCredentials with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.SecurityCredentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SecurityCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または複製物作成会社間のトラフィックをセキュリティで保護するセキュリティ資格情報を設定します。
            </summary>
        <value>セキュリティ資格情報。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedLogId">
      <MemberSignature Language="C#" Value="public string SharedLogId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedLogId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.SharedLogId" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedLogId As String" />
      <MemberSignature Language="F#" Value="member this.SharedLogId : string with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.SharedLogId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、これも含めて、windows fabric ノード上のレプリカの数によって共有されているログ コンテナーの GUID 識別子を設定します。
            既定値は""ログを使用する、グローバル共有ノードのレプリケーターが発生します。
            </summary>
        <value>共有ログ id です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedLogPath">
      <MemberSignature Language="C#" Value="public string SharedLogPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedLogPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.SharedLogPath" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedLogPath As String" />
      <MemberSignature Language="F#" Value="member this.SharedLogPath : string with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.SharedLogPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、これも含めて、ノード上のレプリカの数によって共有されているログのコンテナーに完全なパス名を設定します。
            既定値は""ログを使用する、グローバル共有ノードのレプリケーターが発生します。
            </summary>
        <value>共有のログのパス。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SlowApiMonitoringDuration">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; SlowApiMonitoringDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; SlowApiMonitoringDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.SlowApiMonitoringDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property SlowApiMonitoringDuration As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.SlowApiMonitoringDuration : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.SlowApiMonitoringDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            レプリケーターが警告状態のレポートと、その API が低速な予期された期間より長く時間がかかってを送信するまでの間隔を設定します。
            既定値は、5 分です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThrottlingThresholdFactor">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ThrottlingThresholdFactor { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ThrottlingThresholdFactor" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.ThrottlingThresholdFactor" />
      <MemberSignature Language="VB.NET" Value="Public Property ThrottlingThresholdFactor As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ThrottlingThresholdFactor : Nullable&lt;int&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.ThrottlingThresholdFactor" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の調整のしきい値の係数。 ログの使用は、この値を超えたときに開始する調整 MinLogSizeInMB がタイムアウトします。
            既定値は 3 です。
            </summary>
        <value>調整のしきい値。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="reliableStateManagerReplicatorSettings.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            現在のオブジェクトを表す文字列を返します。
            </summary>
        <returns>
            <see cref="T:System.String" />。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TruncationThresholdFactor">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TruncationThresholdFactor { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TruncationThresholdFactor" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.TruncationThresholdFactor" />
      <MemberSignature Language="VB.NET" Value="Public Property TruncationThresholdFactor As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TruncationThresholdFactor : Nullable&lt;int&gt; with get, set" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings.TruncationThresholdFactor" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または切り捨てのしきい値の係数を設定します。 ログの使用は、この値を超えたときに開始する切り捨て MinLogSizeInMB がタイムアウトします。
            既定値は 2 です。
            </summary>
        <value>切り捨てのしきい値。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>