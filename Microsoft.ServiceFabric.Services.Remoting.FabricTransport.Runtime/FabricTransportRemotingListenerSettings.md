<Type Name="FabricTransportRemotingListenerSettings" FullName="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings">
  <TypeSignature Language="C#" Value="public class FabricTransportRemotingListenerSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FabricTransportRemotingListenerSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricTransportRemotingListenerSettings" />
  <TypeSignature Language="F#" Value="type FabricTransportRemotingListenerSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            FabricTransport リスナーを構成する設定です。
             </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransportRemotingListenerSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            FabricTransportRemotingListenerSettings の新しいインスタンスを作成し、既定値を持つプロパティを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndpointResourceName">
      <MemberSignature Language="C#" Value="public string EndpointResourceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EndpointResourceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.EndpointResourceName" />
      <MemberSignature Language="VB.NET" Value="Public Property EndpointResourceName As String" />
      <MemberSignature Language="F#" Value="member this.EndpointResourceName : string with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.EndpointResourceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            EndpointResourceName は ServiceManifest で指定したエンドポイント リソースの名前です。サービスへのポート番号がリッスンするため使用されます。 
            </summary>
        <value>
            EndpointResourceName とは、サービス マニフェストで定義されているエンドポイント リソースの名前です。
            </value>
        <remarks>
            EndpointResourceName の既定値は"ServiceEndpoint" </remarks>
      </Docs>
    </Member>
    <Member MemberName="HeaderBufferSize">
      <MemberSignature Language="C#" Value="public int HeaderBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 HeaderBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.HeaderBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property HeaderBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.HeaderBufferSize : int with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.HeaderBufferSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            HeaderBufferSize では、各ヘッダーのバッファー、bufferPool のサイズを表します。
             </summary>
        <value>To be added.</value>
        <remarks>
                HeaderBufferSize の既定値は、1024 バイトです。
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="HeaderMaxBufferCount">
      <MemberSignature Language="C#" Value="public int HeaderMaxBufferCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 HeaderMaxBufferCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.HeaderMaxBufferCount" />
      <MemberSignature Language="VB.NET" Value="Public Property HeaderMaxBufferCount As Integer" />
      <MemberSignature Language="F#" Value="member this.HeaderMaxBufferCount : int with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.HeaderMaxBufferCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            HeaderMaxBufferCount、BufferPool に割り当てられているヘッダーのバッファーの最大数を表します。
             </summary>
        <value>To be added.</value>
        <remarks>
                HeaderMaxBufferCount の既定値は 1000 です。
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="KeepAliveTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan KeepAliveTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan KeepAliveTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.KeepAliveTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property KeepAliveTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.KeepAliveTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.KeepAliveTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            KeepAliveTimeout は Tcp keep-alive オプションを構成する方法を提供します。
            </summary>
        <value>として KeepAliveTimeout<see cref="T:System.TimeSpan" /></value>
        <remarks>KeepAliveTimeout タイムアウトの既定値は、TimeSpan.Zero として設定されます。 これは、tcp keepalive オプションを無効にすることを示します。
            特定の時刻より後の接続を終了するロード バランサーを回避するためにこれを構成する必要があるロード バランサーを使用している場合 </remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadFrom">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings LoadFrom (string sectionName, string configPackageName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings LoadFrom(string sectionName, string configPackageName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.LoadFrom(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function LoadFrom (sectionName As String, Optional configPackageName As String = null) As FabricTransportRemotingListenerSettings" />
      <MemberSignature Language="F#" Value="static member LoadFrom : string * string -&gt; Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.LoadFrom (sectionName, configPackageName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sectionName" Type="System.String" />
        <Parameter Name="configPackageName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sectionName">構成ファイル内のセクションの名前です。 存在しない場合、ArgumentException をスローします。</param>
        <param name="configPackageName"> 構成パッケージの名前です。 場合、構成パッケージのパスに見つかりません。 Settings.xml ArgumentException をスローします。 既定の名前は"Config"で指定されていない場合</param>
        <summary>
            サービス設定の構成ファイルで指定されているセクションから FabricTransport 設定を読み込みます settings.xml 
            </summary>
        <returns>FabricTransportRemotingListenerSettings</returns>
        <remarks>
            トランスポート設定を読み込むサービス ファブリックで認識可能であって、構成ファイルで指定されるべきパラメーター名を次に示します。
                
                1. MaxQueueSize -<see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxQueueSize" />時間の長い内の値。
                2. MaxMessageSize -<see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxMessageSize" />値 (バイト単位)。
                3. MaxConcurrentCalls -<see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxConcurrentCalls" />時間の長い内の値。
                4. SecurityCredentials -<see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.SecurityCredentials" />値。
                5. OperationTimeoutInSeconds -<see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.OperationTimeout" />値 (秒)。
                6. KeepAliveTimeoutInSeconds -<see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.KeepAliveTimeout" />値 (秒)。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxConcurrentCalls">
      <MemberSignature Language="C#" Value="public long MaxConcurrentCalls { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxConcurrentCalls" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.MaxConcurrentCalls" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxConcurrentCalls As Long" />
      <MemberSignature Language="F#" Value="member this.MaxConcurrentCalls : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.MaxConcurrentCalls" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            MaxConcurrentCalls 表しますのメッセージの最大数は積極的に、プロセスを同時にサービスします。
             </summary>
        <value>
            MaxConcurrentCalls は、サービスのアクティブなメッセージの数の上限です。
             </value>
        <remarks>
                MaxConcurrentCalls の既定値は、プロセッサの数です。
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxMessageSize">
      <MemberSignature Language="C#" Value="public long MaxMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.MaxMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxMessageSize : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.MaxMessageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            MaxMessageSize では、この設定で構成されるチャネルで受信可能なメッセージの最大サイズを表します。
            </summary>
        <value>バイト単位でメッセージの最大サイズ。
            </value>
        <remarks>
            使用 MaxMessageSize の既定値は 4194304 バイトです。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxQueueSize">
      <MemberSignature Language="C#" Value="public long MaxQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxQueueSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.MaxQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxQueueSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxQueueSize : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.MaxQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この設定で構成されたエンドポイントに対して処理されるときにメッセージを格納するキューの最大サイズ。 
            </summary>
        <value> チャネルからメッセージを受信するキューの最大サイズ 
            </value>
        <remarks>
            既定値は 10,000 メッセージです。</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.OperationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            要求/応答サービス操作の応答メッセージの受信を含め、メッセージを送信するプロセス全体を制御する操作がタイムアウトします。
             このタイムアウトは、コールバック コントラクト メソッドから応答メッセージを送信するときにも適用されます。
            </summary>
        <value>として OperationTimeout<see cref="T:System.TimeSpan" /></value>
        <remarks>操作のタイムアウトの既定値は 5 分として設定します。</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecurityCredentials">
      <MemberSignature Language="C#" Value="public System.Fabric.SecurityCredentials SecurityCredentials { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.SecurityCredentials SecurityCredentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.SecurityCredentials" />
      <MemberSignature Language="VB.NET" Value="Public Property SecurityCredentials As SecurityCredentials" />
      <MemberSignature Language="F#" Value="member this.SecurityCredentials : System.Fabric.SecurityCredentials with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.SecurityCredentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SecurityCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             通信を保護するためのセキュリティ資格情報 
             </summary>
        <value>として SecurityCredentials<see cref="T:System.Fabric.SecurityCredentials" /></value>
        <remarks>
             SecurityCredentials の既定値は SecurityCredential できます型 x509SecurityCredentail None<seealso cref="T:System.Fabric.X509Credentials" />または WindowsCredentials<seealso cref="T:System.Fabric.WindowsCredentials" /></remarks>
      </Docs>
    </Member>
    <Member MemberName="TryLoadFrom">
      <MemberSignature Language="C#" Value="public static bool TryLoadFrom (string sectionName, out Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings remotingListenerSettings, string configPackageName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool TryLoadFrom(string sectionName, [out] class Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings&amp; remotingListenerSettings, string configPackageName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.TryLoadFrom(System.String,Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings@,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function TryLoadFrom (sectionName As String, ByRef remotingListenerSettings As FabricTransportRemotingListenerSettings, Optional configPackageName As String = null) As Boolean" />
      <MemberSignature Language="F#" Value="static member TryLoadFrom : string *  * string -&gt; bool" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.TryLoadFrom (sectionName, remotingListenerSettings, configPackageName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sectionName" Type="System.String" />
        <Parameter Name="remotingListenerSettings" Type="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings&amp;" RefType="out" />
        <Parameter Name="configPackageName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sectionName">構成ファイル内のセクションの名前です。 かどうか、見つからない、false を返します</param>
        <param name="remotingListenerSettings">設定をこのメソッドが戻るとき、 <see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" /> listenersettings 場合に成功しました構成からロードします。 場合は失敗すると、null には、そのセット listenerSettings/&gt; </param>
        <param name="configPackageName"> 構成パッケージの名前です。 構成パッケージのパスに見つかりません。 Settings.xml 場合は、false を返します。 既定の名前は"Config"で指定されていない場合</param>
        <summary>
            サービス設定の構成ファイルで指定されたセクションから FabricTransport 設定をロードしようとしています settings.xml。 
            </summary>
        <returns>
          <see cref="T:System.Boolean" />構成から設定を正常に読み込むを取得するかどうかを指定します。True を返すときに構成が成功したから読み込み、それ以外の場合は false を返します。</returns>
        <remarks>
            トランスポート設定を読み込むサービス ファブリックで認識可能であって、構成ファイルで指定されるべきパラメーター名を次に示します。
                
                1. MaxQueueSize -<see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxQueueSize" />時間の長い内の値。
                2. MaxMessageSize -<see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxMessageSize" />値 (バイト単位)。
                3. MaxConcurrentCalls -<see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxConcurrentCalls" />時間の長い内の値。
                4. SecurityCredentials -<see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.SecurityCredentials" />値。
                5. OperationTimeoutInSeconds -<see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.OperationTimeout" />値 (秒)。
                6. KeepAliveTimeoutInSeconds -<see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.KeepAliveTimeout" />値 (秒)。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>