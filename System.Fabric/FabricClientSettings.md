<Type Name="FabricClientSettings" FullName="System.Fabric.FabricClientSettings">
  <TypeSignature Language="C#" Value="public sealed class FabricClientSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit FabricClientSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClientSettings" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClientSettings" />
  <TypeSignature Language="F#" Value="type FabricClientSettings = class" />
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
      <para>構成設定を表す、<see cref="T:System.Fabric.FabricClient" />クラスです。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricClientSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClientSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.FabricClientSettings" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthTokenBufferSize">
      <MemberSignature Language="C#" Value="public long AuthTokenBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 AuthTokenBufferSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClientSettings.AuthTokenBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthTokenBufferSize As Long" />
      <MemberSignature Language="F#" Value="member this.AuthTokenBufferSize : int64 with get, set" Usage="System.Fabric.FabricClientSettings.AuthTokenBufferSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure Active Directory から認証トークンを取得するときに使用するバッファー サイズを示す値を設定します。
            </summary>
        <value>
            バッファー サイズをバイト単位で返します。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientFriendlyName">
      <MemberSignature Language="C#" Value="public string ClientFriendlyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientFriendlyName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClientSettings.ClientFriendlyName" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientFriendlyName As String" />
      <MemberSignature Language="F#" Value="member this.ClientFriendlyName : string with get, set" Usage="System.Fabric.FabricClientSettings.ClientFriendlyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得またはデバッグするための Service Fabric トレースに表示されるクライアントのフレンドリ名を設定します。</para>
        </summary>
        <value>
          <para>Service Fabric のデバッグ トレースに表示されるクライアント フレンドリ名。</para>
        </value>
        <remarks>
          <para>既定値は null と、クライアントのフレンドリ名が自動的に生成されますを GUID として内部的にします。</para>
          <para>複数のクライアントは、同じプロセスから、または同じノードに作成でき場合、は、名前に一意の識別子を追加することをお勧めします。
            たとえば、MyProcessIdentifier - {guid} です。
            これにより、トレースが生成するクライアントにさまざまな操作を追跡できます。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionIdleTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan ConnectionIdleTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan ConnectionIdleTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClientSettings.ConnectionIdleTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionIdleTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.ConnectionIdleTimeout : TimeSpan with get, set" Usage="System.Fabric.FabricClientSettings.ConnectionIdleTimeout" />
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
            このパラメーターは廃止されました。 これは、次のリリースで削除されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionInitializationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan ConnectionInitializationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan ConnectionInitializationTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClientSettings.ConnectionInitializationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionInitializationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.ConnectionInitializationTimeout : TimeSpan with get, set" Usage="System.Fabric.FabricClientSettings.ConnectionInitializationTimeout" />
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
          <para>取得または設定が、タイムアウトするまで、現在のゲートウェイ アドレスが有効な接続に応答しない場合他のさまざまなアドレスがランダムに選択からゲートウェイ アドレスのコレクション。</para>
        </summary>
        <value>
          <para>現在のゲートウェイ アドレスが有効な接続に応答しない後にタイムアウトします。</para>
        </value>
        <remarks>
          <para>既定値、<see cref="P:System.Fabric.FabricClientSettings.ConnectionInitializationTimeout" />プロパティは 2 秒です。</para>
          <para><see cref="P:System.Fabric.FabricClientSettings.ConnectionInitializationTimeout" />プロパティには、値より小さくする必要があります、<see cref="P:System.Fabric.FabricClientSettings.ServiceChangePollInterval" />プロパティです。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthOperationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan HealthOperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan HealthOperationTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClientSettings.HealthOperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthOperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.HealthOperationTimeout : TimeSpan with get, set" Usage="System.Fabric.FabricClientSettings.HealthOperationTimeout" />
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
          <para>取得または設定タイムアウト正常性状態操作要求、クライアントからゲートウェイにします。</para>
        </summary>
        <value>
          <para>正常操作の要求をクライアントからゲートウェイにタイムアウトしました。</para>
        </value>
        <remarks>
          <para>既定値、<see cref="P:System.Fabric.FabricClientSettings.HealthOperationTimeout" />プロパティは、120 秒です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthReportRetrySendInterval">
      <MemberSignature Language="C#" Value="public TimeSpan HealthReportRetrySendInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan HealthReportRetrySendInterval" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClientSettings.HealthReportRetrySendInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthReportRetrySendInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.HealthReportRetrySendInterval : TimeSpan with get, set" Usage="System.Fabric.FabricClientSettings.HealthReportRetrySendInterval" />
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
          <para>取得またはどの正常性で正常性マネージャーによってがまだ確認されていないレポートが再送信の再試行間隔を設定します。</para>
        </summary>
        <value>
          <para>再試行間隔は、どの正常性で正常性マネージャーによってがまだ確認されていないレポートが再送信します。</para>
        </value>
        <remarks>
          <para>既定値、<see cref="P:System.Fabric.FabricClientSettings.HealthReportRetrySendInterval" />プロパティは 30 秒です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthReportSendInterval">
      <MemberSignature Language="C#" Value="public TimeSpan HealthReportSendInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan HealthReportSendInterval" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClientSettings.HealthReportSendInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthReportSendInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.HealthReportSendInterval : TimeSpan with get, set" Usage="System.Fabric.FabricClientSettings.HealthReportSendInterval" />
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
          <para>取得またはに正常性レポートは正常性マネージャーに送信される間隔を設定します。</para>
        </summary>
        <value>
          <para>どの正常性レポートが送信される正常性マネージャーへの間隔。</para>
        </value>
        <remarks>
          <para>既定値、<see cref="P:System.Fabric.FabricClientSettings.HealthReportSendInterval" />プロパティは 30 秒です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="KeepAliveInterval">
      <MemberSignature Language="C#" Value="public TimeSpan KeepAliveInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan KeepAliveInterval" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClientSettings.KeepAliveInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property KeepAliveInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.KeepAliveInterval : TimeSpan with get, set" Usage="System.Fabric.FabricClientSettings.KeepAliveInterval" />
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
          <para>間隔を取得、<see cref="T:System.Fabric.FabricClient" />接続されているエンドポイントは ping を実行します。</para>
        </summary>
        <value>
          <para>間隔、<see cref="T:System.Fabric.FabricClient" />接続されているエンドポイントは ping を実行します。</para>
        </value>
        <remarks>
          <para>既定値、<see cref="P:System.Fabric.FabricClientSettings.KeepAliveInterval" />プロパティは 0 秒です。</para>
          <para>後にこのプロパティを更新することはできません、<see cref="T:System.Fabric.FabricClient" />が開かれています。
            このプロパティはスロー設定、<see cref="T:System.ArgumentException" />例外。</para>
          <para>
            <see cref="T:System.Fabric.FabricClient" />保留中の操作がある限り、ping を実行し続けます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="NotificationCacheUpdateTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan NotificationCacheUpdateTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan NotificationCacheUpdateTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClientSettings.NotificationCacheUpdateTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property NotificationCacheUpdateTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.NotificationCacheUpdateTimeout : TimeSpan with get, set" Usage="System.Fabric.FabricClientSettings.NotificationCacheUpdateTimeout" />
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
          <para>取得またはサービスの通知への応答でローカル キャッシュを更新するためのタイムアウトを設定します。 既定値は 30 秒です。</para>
        </summary>
        <value>
          <para>サービスの通知への応答でローカル キャッシュの更新のタイムアウト。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NotificationGatewayConnectionTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan NotificationGatewayConnectionTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan NotificationGatewayConnectionTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClientSettings.NotificationGatewayConnectionTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property NotificationGatewayConnectionTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.NotificationGatewayConnectionTimeout : TimeSpan with get, set" Usage="System.Fabric.FabricClientSettings.NotificationGatewayConnectionTimeout" />
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
          <para>取得またはクライアントがサービスの通知に登録されている場合は、再接続プロトコルを実行するためのタイムアウトを設定します。 既定値は 30 秒です。 </para>
        </summary>
        <value>
          <para>クライアントがサービスの通知に登録されている場合は、再接続プロトコルを実行するためのタイムアウト。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionLocationCacheBucketCount">
      <MemberSignature Language="C#" Value="public long PartitionLocationCacheBucketCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 PartitionLocationCacheBucketCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClientSettings.PartitionLocationCacheBucketCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionLocationCacheBucketCount As Long" />
      <MemberSignature Language="F#" Value="member this.PartitionLocationCacheBucketCount : int64 with get, set" Usage="System.Fabric.FabricClientSettings.PartitionLocationCacheBucketCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得またはクライアントのサービスの解像度のキャッシュで使用される、バケット数を設定します。</para>
        </summary>
        <value>
          <para>クライアントのサービスの解像度のキャッシュで使用されるバケットの数。</para>
        </value>
        <remarks>
          <para>既定値は 1024 です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionLocationCacheLimit">
      <MemberSignature Language="C#" Value="public long PartitionLocationCacheLimit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 PartitionLocationCacheLimit" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClientSettings.PartitionLocationCacheLimit" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionLocationCacheLimit As Long" />
      <MemberSignature Language="F#" Value="member this.PartitionLocationCacheLimit : int64 with get, set" Usage="System.Fabric.FabricClientSettings.PartitionLocationCacheLimit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>クライアントのキャッシュの場所エントリの最大数を取得します。</para>
        </summary>
        <value>
          <para>クライアントのキャッシュの場所エントリの最大数。</para>
        </value>
        <remarks>
          <para>既定値、<see cref="P:System.Fabric.FabricClientSettings.PartitionLocationCacheLimit" />プロパティは 1000 です。</para>
          <para><see cref="P:System.Fabric.FabricClientSettings.PartitionLocationCacheLimit" />プロパティは更新できません。 このプロパティはスロー設定、<see cref="T:System.ArgumentException" />例外。</para>
          <para>キャッシュ制限に達したときに、最も古いエントリが最初に破棄されます。 既定値は 100 です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceChangePollInterval">
      <MemberSignature Language="C#" Value="public TimeSpan ServiceChangePollInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan ServiceChangePollInterval" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClientSettings.ServiceChangePollInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceChangePollInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.ServiceChangePollInterval : TimeSpan with get, set" Usage="System.Fabric.FabricClientSettings.ServiceChangePollInterval" />
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
          <para>取得または設定タイムアウト サービスの変更通知要求、クライアントからすべての登録されたコールバックのゲートウェイにします。</para>
        </summary>
        <value>
          <para>サービスのタイムアウトは、すべての登録されたコールバックのゲートウェイに、クライアントからの通知要求を変更します。</para>
        </value>
        <remarks>
          <para>既定値、<see cref="P:System.Fabric.FabricClientSettings.ServiceChangePollInterval" />プロパティは、120 秒です。</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>