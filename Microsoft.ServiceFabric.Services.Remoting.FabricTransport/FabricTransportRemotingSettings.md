<Type Name="FabricTransportRemotingSettings" FullName="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings">
  <TypeSignature Language="C#" Value="public class FabricTransportRemotingSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FabricTransportRemotingSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricTransportRemotingSettings" />
  <TypeSignature Language="F#" Value="type FabricTransportRemotingSettings = class" />
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
            FabricTransport 通信を構成する設定を表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransportRemotingSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            既定値を持つ新しい FabricTransportRemotingSettings を作成します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan ConnectTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan ConnectTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.ConnectTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.ConnectTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.ConnectTimeout" />
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
            取得または設定を正常に確立する接続の許可された最大時間。
            </summary>
        <value>として ConnectTimeout<see cref="T:System.TimeSpan" />です。</value>
        <remarks>ConnectTimeout タイムアウトの既定値は 5 秒に設定されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="HeaderBufferSize">
      <MemberSignature Language="C#" Value="public int HeaderBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 HeaderBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.HeaderBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property HeaderBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.HeaderBufferSize : int with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.HeaderBufferSize" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.HeaderMaxBufferCount" />
      <MemberSignature Language="VB.NET" Value="Public Property HeaderMaxBufferCount As Integer" />
      <MemberSignature Language="F#" Value="member this.HeaderMaxBufferCount : int with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.HeaderMaxBufferCount" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.KeepAliveTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property KeepAliveTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.KeepAliveTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.KeepAliveTimeout" />
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
            取得または Tcp の keep-alive オプションを構成する方法を提供する KeepAliveTimeout を設定します。
            </summary>
        <value>として KeepAliveTimeout<see cref="T:System.TimeSpan" />です。</value>
        <remarks>KeepAliveTimeout タイムアウトの既定値は、TimeSpan.Zero として設定されます。 これは、tcp keepalive オプションを無効にすることを示します。
            ロード バランサーを使用している場合は、特定の時刻より後の接続を終了するロード バランサーを回避するためにこれを構成する必要があります。 </remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadFrom">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings LoadFrom (string sectionName, string filepath = null, string configPackageName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings LoadFrom(string sectionName, string filepath, string configPackageName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.LoadFrom(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function LoadFrom (sectionName As String, Optional filepath As String = null, Optional configPackageName As String = null) As FabricTransportRemotingSettings" />
      <MemberSignature Language="F#" Value="static member LoadFrom : string * string * string -&gt; Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.LoadFrom (sectionName, filepath, configPackageName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sectionName" Type="System.String" />
        <Parameter Name="filepath" Type="System.String" />
        <Parameter Name="configPackageName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sectionName">構成ファイル内のセクションの名前。 場合、構成ファイルに見つかりません。 セクションは、ArgumentException をスローします。</param>
        <param name="filepath">設定がから読み込まれるファイルの完全パス。 指定しない場合、これはまず既定の構成パッケージ"Config"から読み込む場合は、見つからないから読み込みます"ClientExeName.Settings.xml"の設定がクライアント Exe ディレクトリに存在します。 </param>
        <param name="configPackageName"> 構成パッケージの名前です。その null または空がチェック ファイルのパスでファイルをします。</param>
        <summary>
            構成ファイルで指定された sectionName から FabricTransport 設定を読み込みます。 ファイル パスを使用して、またはサービス マニフェストで指定された構成パッケージの名前を使用して、構成ファイルを指定できます。
            ConfigPackageName を使用して構成を読み込むことはまずします。 configPackageName が指定されていない場合は、ファイル パスから読み込むしてみます。
            </summary>
        <returns>FabricTransportRemotingSettings</returns>
        <remarks>
            トランスポート設定を読み込むサービス ファブリックで認識可能であって、構成ファイルで指定されるべきパラメーター名を次に示します。
                
                1. MaxQueueSize -<see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxQueueSize" />時間の長い内の値。
                2. MaxMessageSize -<see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxMessageSize" />値 (バイト単位)。
                3. MaxConcurrentCalls -<see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxConcurrentCalls" />時間の長い内の値。
                4. SecurityCredentials -<see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.SecurityCredentials" />値。
                5. OperationTimeoutInSeconds -<see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.OperationTimeout" />値 (秒)。
                6. KeepAliveTimeoutInSeconds -<see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.KeepAliveTimeout" />値 (秒)。
                7. ConnectTimeoutInMilliseconds -<see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.ConnectTimeout" />値 (ミリ秒)。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxConcurrentCalls">
      <MemberSignature Language="C#" Value="public long MaxConcurrentCalls { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxConcurrentCalls" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxConcurrentCalls" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxConcurrentCalls As Long" />
      <MemberSignature Language="F#" Value="member this.MaxConcurrentCalls : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxConcurrentCalls" />
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
            取得または設定のメッセージの最大数アクティブにサービス プロセス一度に 1 つ。
             </summary>
        <value>
            MaxConcurrentCalls は、サービスのアクティブなメッセージの数の上限です。
             </value>
        <remarks>
                MaxConcurrentCalls の既定値は 16 * プロセッサの数。
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxMessageSize">
      <MemberSignature Language="C#" Value="public long MaxMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxMessageSize : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxMessageSize" />
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
            取得または、この設定で構成されるチャネルで受信できるメッセージの最大サイズを設定します。
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
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxQueueSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxQueueSize : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxQueueSize" />
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
            取得または設定が、この設定で構成されたエンドポイントに対して処理されるときにメッセージを格納するキューの最大サイズ。 
            </summary>
        <value>チャネルからメッセージを受信するキューの最大サイズ。 
            </value>
        <remarks>
            既定値は 10,000 メッセージです。</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.OperationTimeout" />
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
            取得または操作の要求/応答サービス操作の応答メッセージの受信を含め、メッセージを送信するプロセス全体を制御するタイムアウトを設定します。
             このタイムアウトは、コールバック コントラクト メソッドから応答メッセージを送信するときにも適用されます。
            </summary>
        <value>として OperationTimeout<see cref="T:System.TimeSpan" />です。</value>
        <remarks>操作のタイムアウトの既定値は 5 分として設定されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecurityCredentials">
      <MemberSignature Language="C#" Value="public System.Fabric.SecurityCredentials SecurityCredentials { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.SecurityCredentials SecurityCredentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.SecurityCredentials" />
      <MemberSignature Language="VB.NET" Value="Public Property SecurityCredentials As SecurityCredentials" />
      <MemberSignature Language="F#" Value="member this.SecurityCredentials : System.Fabric.SecurityCredentials with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.SecurityCredentials" />
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
             取得または通信のセキュリティ保護するセキュリティ資格情報を設定します。 
             </summary>
        <value>として資格情報、セキュリティ<see cref="T:System.Fabric.SecurityCredentials" />です。
             </value>
        <remarks>
             SecurityCredentials の既定値は None です。
             SecurityCredential できます型 x509SecurityCredentail<seealso cref="T:System.Fabric.X509Credentials" />または WindowsCredentials<seealso cref="T:System.Fabric.WindowsCredentials" />です。
              </remarks>
      </Docs>
    </Member>
    <Member MemberName="TryLoadFrom">
      <MemberSignature Language="C#" Value="public static bool TryLoadFrom (string sectionName, out Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings settings, string filepath = null, string configPackageName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool TryLoadFrom(string sectionName, [out] class Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings&amp; settings, string filepath, string configPackageName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.TryLoadFrom(System.String,Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings@,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function TryLoadFrom (sectionName As String, ByRef settings As FabricTransportRemotingSettings, Optional filepath As String = null, Optional configPackageName As String = null) As Boolean" />
      <MemberSignature Language="F#" Value="static member TryLoadFrom : string *  * string * string -&gt; bool" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.TryLoadFrom (sectionName, settings, filepath, configPackageName)" />
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
        <Parameter Name="settings" Type="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings&amp;" RefType="out" />
        <Parameter Name="filepath" Type="System.String" />
        <Parameter Name="configPackageName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sectionName">構成ファイル内のセクションの名前。 場合、構成ファイルに見つかりません。 セクションは、false 戻ります。</param>
        <param name="settings">設定をこのメソッドが戻るとき、<see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings" />設定場合構成が成功したからロードします。 場合、そのセットの設定を null には失敗します。 </param>
        <param name="filepath">設定がから読み込まれるファイルの完全パス。 指定しない場合、これはまず既定の構成パッケージ"Config"から読み込む場合は、見つからないから読み込みます"ClientExeName.Settings.xml"の設定がクライアント Exe ディレクトリに存在します。 </param>
        <param name="configPackageName">構成パッケージの名前。 その null または空がチェック ファイルのパスでファイルをします。</param>
        <summary>
            構成ファイルで指定された sectionName から FabricTransport 設定の読み込みを再試行してください。
            ファイル パスを使用して、またはサービス マニフェストで指定された構成パッケージの名前を使用して、構成ファイルを指定できます。
            ConfigPackageName を使用して構成を読み込むことはまずします。 configPackageName が指定されていない場合は、ファイル パスから読み込むしてみます。
            </summary>
        <returns>
          <see cref="T:System.Boolean" />構成から設定を正常に読み込むを取得するかどうかを指定します。True を返すときに構成が成功したから読み込み、それ以外の場合は false を返します。 </returns>
        <remarks>
            トランスポート設定を読み込むサービス ファブリックで認識可能であって、構成ファイルで指定されるべきパラメーター名を次に示します。
                
                1. MaxQueueSize -<see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxQueueSize" />時間の長い内の値。
                2. MaxMessageSize -<see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxMessageSize" />値 (バイト単位)。
                3. MaxConcurrentCalls -<see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxConcurrentCalls" />時間の長い内の値。
                4. SecurityCredentials -<see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.SecurityCredentials" />値。
                5. OperationTimeoutInSeconds -<see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.OperationTimeout" />値 (秒)。
                6. KeepAliveTimeoutInSeconds -<see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.KeepAliveTimeout" />値 (秒)。
                7. ConnectTimeoutInMilliseconds -<see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.ConnectTimeout" />値 (ミリ秒)。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>