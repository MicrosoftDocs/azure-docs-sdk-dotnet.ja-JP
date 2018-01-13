<Type Name="ServicePartitionResolver" FullName="Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver">
  <TypeSignature Language="C#" Value="public class ServicePartitionResolver : Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServicePartitionResolver extends System.Object implements class Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" />
  <TypeSignature Language="VB.NET" Value="Public Class ServicePartitionResolver&#xA;Implements IServicePartitionResolver" />
  <TypeSignature Language="F#" Value="type ServicePartitionResolver = class&#xA;    interface IServicePartitionResolver" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para>
            使用して、サービス パーティションの競合回避モジュールのクラスを実装して、 <see cref="T:System.Fabric.FabricClient">FabricClient の</see><see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />サービス解決のためのメソッドをそのメソッドからのエラーに戻る/再試行メカニズムを実装します。
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePartitionResolver (Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate createFabricClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate createFabricClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.#ctor(Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (createFabricClient As CreateFabricClientDelegate)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver : Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate -&gt; Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" Usage="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver createFabricClient" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="createFabricClient" Type="Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate" />
      </Parameters>
      <Docs>
        <param name="createFabricClient">Fabric クライアントを作成するデリゲート。</param>
        <summary>
            FabricClient のインスタンスを作成する特定のデリゲートを呼び出すの ServicePartitionResolver をインスタンス化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePartitionResolver (params string[] connectionEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string[] connectionEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.#ctor(System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (ParamArray connectionEndpoints As String())" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver : string[] -&gt; Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" Usage="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver connectionEndpoints" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="connectionEndpoints">クラスターの管理エンドポイントの配列です。</param>
        <summary>
            ServicePartitionResolver をインスタンス化は、特定 connectionEndpoints を使用して、FabricClient の新しいインスタンスを作成します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePartitionResolver (Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate createFabricClient, Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate recreateFabricClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate createFabricClient, class Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate recreateFabricClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.#ctor(Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate,Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (createFabricClient As CreateFabricClientDelegate, recreateFabricClient As CreateFabricClientDelegate)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver : Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate * Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate -&gt; Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" Usage="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver (createFabricClient, recreateFabricClient)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="createFabricClient" Type="Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate" />
        <Parameter Name="recreateFabricClient" Type="Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate" />
      </Parameters>
      <Docs>
        <param name="createFabricClient">Fabric クライアントを作成するデリゲート。</param>
        <param name="recreateFabricClient">Fabric クライアントを再作成するデリゲート。</param>
        <summary>
          <para>
            取得する最初のデリゲートを呼び出すの ServicePartionResolver をインスタンス化、 <see cref="T:System.Fabric.FabricClient">FabricClient。</see>です。
            パーティションの解決時に、FabricClient オブジェクトが破棄を取得し、2 番目のデリゲートを指定すると場合、2 番目のデリゲートを使用、FabricClient をもう一度取得されます。 2 番目のデリゲートは、破棄を取得または FabricClient が最初のデリゲートで作成された場合、FabricClient を作成する別の方法を指定する方法を提供します。
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePartitionResolver (System.Fabric.FabricClientSettings settings, params string[] connectionEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.FabricClientSettings settings, string[] connectionEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.#ctor(System.Fabric.FabricClientSettings,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (settings As FabricClientSettings, ParamArray connectionEndpoints As String())" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver : System.Fabric.FabricClientSettings * string[] -&gt; Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" Usage="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver (settings, connectionEndpoints)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="settings" Type="System.Fabric.FabricClientSettings" />
        <Parameter Name="connectionEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="settings">Fabric クライアント設定します。</param>
        <param name="connectionEndpoints">クラスターの管理エンドポイントの配列です。</param>
        <summary>
            ServicePartitionResolver をインスタンス化、FabricClient の新しいインスタンスを作成する指定された FabricClient 設定と、connectionEndpoints を使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePartitionResolver (System.Fabric.SecurityCredentials credential, params string[] connectionEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.SecurityCredentials credential, string[] connectionEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.#ctor(System.Fabric.SecurityCredentials,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credential As SecurityCredentials, ParamArray connectionEndpoints As String())" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver : System.Fabric.SecurityCredentials * string[] -&gt; Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" Usage="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver (credential, connectionEndpoints)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credential" Type="System.Fabric.SecurityCredentials" />
        <Parameter Name="connectionEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="credential">Fabric クライアントのセキュリティ資格情報。</param>
        <param name="connectionEndpoints">クラスターの管理エンドポイントの配列です。</param>
        <summary>
            ServicePartitionResolver をインスタンス化、FabricClient の新しいインスタンスを作成する特定のセキュリティ資格情報と、connectionEndpoints を使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePartitionResolver (System.Fabric.SecurityCredentials credential, System.Fabric.FabricClientSettings settings, params string[] connectionEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.SecurityCredentials credential, class System.Fabric.FabricClientSettings settings, string[] connectionEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.#ctor(System.Fabric.SecurityCredentials,System.Fabric.FabricClientSettings,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credential As SecurityCredentials, settings As FabricClientSettings, ParamArray connectionEndpoints As String())" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver : System.Fabric.SecurityCredentials * System.Fabric.FabricClientSettings * string[] -&gt; Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" Usage="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver (credential, settings, connectionEndpoints)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credential" Type="System.Fabric.SecurityCredentials" />
        <Parameter Name="settings" Type="System.Fabric.FabricClientSettings" />
        <Parameter Name="connectionEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="credential">Fabric クライアントのセキュリティ資格情報。</param>
        <param name="settings">Fabric クライアント設定します。</param>
        <param name="connectionEndpoints">クラスターの管理エンドポイントの配列です。</param>
        <summary>
            ServicePartitionResolver をインスタンス化、FabricClient の新しいインスタンスを作成する特定のセキュリティ資格情報と FabricClient 設定、connectionEndpoints を使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultMaxRetryBackoffInterval">
      <MemberSignature Language="C#" Value="public static readonly TimeSpan DefaultMaxRetryBackoffInterval;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly valuetype System.TimeSpan DefaultMaxRetryBackoffInterval" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.DefaultMaxRetryBackoffInterval" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly DefaultMaxRetryBackoffInterval As TimeSpan " />
      <MemberSignature Language="F#" Value=" staticval mutable DefaultMaxRetryBackoffInterval : TimeSpan" Usage="Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.DefaultMaxRetryBackoffInterval" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            既定最大バックオフ時間 maxRetryBackoffInterval 引数を明示的に指定せずにメソッドが呼び出されたときに、再試行する前に ServicePartitionResolver の ResolveAsync メソッドで使用します。 既定値は、5 秒です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultResolveTimeout">
      <MemberSignature Language="C#" Value="public static readonly TimeSpan DefaultResolveTimeout;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly valuetype System.TimeSpan DefaultResolveTimeout" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.DefaultResolveTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly DefaultResolveTimeout As TimeSpan " />
      <MemberSignature Language="F#" Value=" staticval mutable DefaultResolveTimeout : TimeSpan" Usage="Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.DefaultResolveTimeout" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            既定値は、try の ResolveAsync メソッドで使用される単位のタイムアウトを解決する<see cref="T:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" />resolveTimeoutPerTry 引数を明示的に指定することがなく呼び出されるとします。 既定値は 30 秒です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDefault">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver GetDefault ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver GetDefault() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.GetDefault" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetDefault () As ServicePartitionResolver" />
      <MemberSignature Language="F#" Value="static member GetDefault : unit -&gt; Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" Usage="Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.GetDefault " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            ServicePartitionResolver 既定値を取得します。
            <remarks><para>既定のサービス パーティションの競合回避モジュール インスタンスがローカルを使用して<see href="https://docs.microsoft.com/en-us/dotnet/api/system.fabric.fabricclient#System_Fabric_FabricClient__ctor">fabric クライアント</see>です。適切なエンドポイントまたは FabricClient を使用して ServicePartitionResolver を作成し、既定値を更新する方法を推奨は、リモート クラスターで実行されているサービスを解決するのには、ServicePartitionResolver を使用している場合ServicePartitionResolver です。</para></remarks></summary>
        <returns>既定値<see cref="T:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" /></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveAsync (System.Fabric.ResolvedServicePartition previousRsp, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveAsync(class System.Fabric.ResolvedServicePartition previousRsp, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.ResolveAsync(System.Fabric.ResolvedServicePartition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ResolveAsync : System.Fabric.ResolvedServicePartition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="servicePartitionResolver.ResolveAsync (previousRsp, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="previousRsp" Type="System.Fabric.ResolvedServicePartition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="previousRsp">クライアントが ResolveAsync() メソッドの以前の呼び出しから取得した解決済みのサービス パーティション。</param>
        <param name="cancellationToken">
          <para>
            この CancellationToken は、この操作を確認します。 取り消す必要がある操作の通知に使用されます。
            </para>
        </param>
        <summary>
            指定されたサービスのパーティションを FabricClient を呼び出すことによって解決<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />再試行可能エラー時に戻る/再試行を持つメソッドです。 これには、解決済みのサービス パーティション内に、ResolveAsync() メソッドの以前の呼び出しを使用した取得しました。 このメソッドのオーバー ロードは、クライアントが、解決済みのサービス パーティションを持つことが有効ではなくなったことを確認する場合に使用されます。
            </summary>
        <returns>
            A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。 タスクから結果が、<see cref="T:System.Fabric.ResolvedServicePartition" />サービス エンドポイントを含む、解決済みのサービス パーティションに関する情報を含むオブジェクト。
            </returns>
        <remarks>
          <para>
            このメソッドは、すべての一時的な例外で再試行します。 このメソッドの最大実行時間を制限する場合、作成する必要があります、<see href="https://docs.microsoft.com/en-us/dotnet/core/api/system.threading.cancellationtokensource#System_Threading_CancellationTokenSource__ctor_System_TimeSpan_">その最大実行時間に関連付けられたキャンセル トークン</see>そのキャンセル トークンをこのメソッドに渡します。
            </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricServiceNotFoundException">
          <para>
            このメソッドは、サービスが以前に解決されましたが、クラスター内に存在がなくなった場合、FabricServiceNotFoundExcepion をスローできます。
            </para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveAsync (Uri serviceUri, Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveAsync(class System.Uri serviceUri, class Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.ResolveAsync(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ResolveAsync : Uri * Microsoft.ServiceFabric.Services.Client.ServicePartitionKey * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="servicePartitionResolver.ResolveAsync (serviceUri, partitionKey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="Microsoft.ServiceFabric.Services.Client.ServicePartitionKey" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceUri">解決するのには、サービス インスタンスの名前です。</param>
        <param name="partitionKey">
          <para>
            <see cref="T:Microsoft.ServiceFabric.Services.Client.ServicePartitionKey">キー</see>サービス インスタンスの対象のパーティションを指定します。 <see cref="T:System.Fabric.ServicePartitionKind">パーティション</see>で指定されてキーは、パーティション スキームの一致使用サービス インスタンスを作成します。
            </para>
        </param>
        <param name="cancellationToken">
          <para>
            この CancellationToken は、この操作を確認します。 取り消す必要がある操作の通知に使用されます。
            </para>
        </param>
        <summary>
          <para>
            指定されたサービスのパーティションを FabricClient を呼び出すことによって解決<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />メソッドです。 既定の設定を使用してこの<see cref="F:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.DefaultResolveTimeout">タイムアウト</see>と<see cref="F:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.DefaultMaxRetryBackoffInterval">バックオフ再試行</see>間隔。
            </para>
        </summary>
        <returns>
            A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。 タスクから結果が、<see cref="T:System.Fabric.ResolvedServicePartition" />サービス エンドポイントを含む、解決済みのサービス パーティションに関する情報を含むオブジェクト。
            </returns>
        <remarks>
          <para>
            このメソッドは、すべての一時的な例外で再試行します。 このメソッドの最大実行時間を制限する場合、作成する必要があります、<see href="https://docs.microsoft.com/en-us/dotnet/core/api/system.threading.cancellationtokensource#System_Threading_CancellationTokenSource__ctor_System_TimeSpan_">その最大実行時間に関連付けられたキャンセル トークン</see>そのキャンセル トークンをこのメソッドに渡します。
            </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricServiceNotFoundException">
          <para>
            指定した serviceUri に一致するクラスターでサービス インスタンスがない場合、このメソッドは、FabricServiceNotFoundExcepion をスローできます。
            </para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            このメソッドは、ServicePartitionKey で指定されたスキームがサービス インスタンスの作成に使用されるスキームと一致しない場合、FabricException をスローできます。
            関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/">エラーと例外</see>FabricClient の一般的な障害を処理するためです。
            </para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveAsync (System.Fabric.ResolvedServicePartition previousRsp, TimeSpan resolveTimeoutPerTry, TimeSpan maxRetryBackoffInterval, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveAsync(class System.Fabric.ResolvedServicePartition previousRsp, valuetype System.TimeSpan resolveTimeoutPerTry, valuetype System.TimeSpan maxRetryBackoffInterval, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.ResolveAsync(System.Fabric.ResolvedServicePartition,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResolveAsync : System.Fabric.ResolvedServicePartition * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;&#xA;override this.ResolveAsync : System.Fabric.ResolvedServicePartition * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="servicePartitionResolver.ResolveAsync (previousRsp, resolveTimeoutPerTry, maxRetryBackoffInterval, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver.ResolveAsync(System.Fabric.ResolvedServicePartition,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="previousRsp" Type="System.Fabric.ResolvedServicePartition" />
        <Parameter Name="resolveTimeoutPerTry" Type="System.TimeSpan" />
        <Parameter Name="maxRetryBackoffInterval" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="previousRsp">クライアントが ResolveAsync() メソッドの以前の呼び出しから取得した解決済みのサービス パーティション。</param>
        <param name="resolveTimeoutPerTry">FabricClient に渡されるタイムアウト<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />メソッド </param>
        <param name="maxRetryBackoffInterval">
          <para>
            ときに再試行する前にバックオフする最大間隔 FabricClient の<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />メソッド再試行可能例外で失敗します。 元に戻し間隔には、実際にはランダムな時間間隔が指定された maxRetryBackoffInterval 小さいします。
            </para>
        </param>
        <param name="cancellationToken">
          <para>
            この CancellationToken は、この操作を確認します。 取り消す必要がある操作の通知に使用されます。
            </para>
        </param>
        <summary>
            指定されたサービスのパーティションを FabricClient を呼び出すことによって解決<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />再試行可能エラー時に戻る/再試行を持つメソッドです。 これには、解決済みのサービス パーティション内に、ResolveAsync() メソッドの以前の呼び出しを使用した取得しました。 このメソッドのオーバー ロードは、クライアントが、解決済みのサービス パーティションを持つことが有効ではなくなったことを確認する場合に使用されます。
            </summary>
        <returns>
            A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。 タスクから結果が、<see cref="T:System.Fabric.ResolvedServicePartition" />サービス エンドポイントを含む、解決済みのサービス パーティションに関する情報を含むオブジェクト。
            </returns>
        <remarks>
          <para>
            このメソッドは、すべての一時的な例外で再試行します。 このメソッドの最大実行時間を制限する場合、作成する必要があります、<see href="https://docs.microsoft.com/en-us/dotnet/core/api/system.threading.cancellationtokensource#System_Threading_CancellationTokenSource__ctor_System_TimeSpan_">その最大実行時間に関連付けられたキャンセル トークン</see>そのキャンセル トークンをこのメソッドに渡します。
            </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricServiceNotFoundException">
          <para>
            このメソッドは、サービスが以前に解決されましたが、クラスター内に存在がなくなった場合、FabricServiceNotFoundExcepion をスローできます。
            </para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveAsync (Uri serviceUri, Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, TimeSpan resolveTimeoutPerTry, TimeSpan maxRetryBackoffInterval, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveAsync(class System.Uri serviceUri, class Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, valuetype System.TimeSpan resolveTimeoutPerTry, valuetype System.TimeSpan maxRetryBackoffInterval, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.ResolveAsync(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResolveAsync : Uri * Microsoft.ServiceFabric.Services.Client.ServicePartitionKey * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;&#xA;override this.ResolveAsync : Uri * Microsoft.ServiceFabric.Services.Client.ServicePartitionKey * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="servicePartitionResolver.ResolveAsync (serviceUri, partitionKey, resolveTimeoutPerTry, maxRetryBackoffInterval, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver.ResolveAsync(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="Microsoft.ServiceFabric.Services.Client.ServicePartitionKey" />
        <Parameter Name="resolveTimeoutPerTry" Type="System.TimeSpan" />
        <Parameter Name="maxRetryBackoffInterval" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceUri">解決するのには、サービス インスタンスの名前です。</param>
        <param name="partitionKey">
          <para>
            <see cref="T:Microsoft.ServiceFabric.Services.Client.ServicePartitionKey">キー</see>サービス インスタンスの対象のパーティションを指定します。 <see cref="T:System.Fabric.ServicePartitionKind">パーティション</see>で指定されてキーは、パーティション スキームの一致使用サービス インスタンスを作成します。
            </para>
        </param>
        <param name="resolveTimeoutPerTry">FabricClient に渡されるタイムアウト<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />メソッドです。</param>
        <param name="maxRetryBackoffInterval">
          <para>
            ときに再試行する前にバックオフする最大間隔 FabricClient の<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />メソッド再試行可能例外で失敗します。 元に戻し間隔には、実際にはランダムな時間間隔が指定された maxRetryBackoffInterval 小さいします。
            </para>
        </param>
        <param name="cancellationToken">
          <para>
            この CancellationToken は、この操作を確認します。 取り消す必要がある操作の通知に使用されます。
            </para>
        </param>
        <summary>
            指定されたサービスのパーティションを FabricClient を呼び出すことによって解決<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />メソッドを指定したタイムアウトと再試行可能エラー時に戻る/再試行します。
            </summary>
        <returns>
            A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。 タスクから結果が、<see cref="T:System.Fabric.ResolvedServicePartition" />サービス エンドポイントを含む、解決済みのサービス パーティションに関する情報を含むオブジェクト。
            </returns>
        <remarks>
          <para>
            このメソッドは、すべての一時的な例外で再試行します。 このメソッドの最大実行時間を制限する場合、作成する必要があります、<see href="https://docs.microsoft.com/en-us/dotnet/core/api/system.threading.cancellationtokensource#System_Threading_CancellationTokenSource__ctor_System_TimeSpan_">その最大実行時間に関連付けられたキャンセル トークン</see>そのキャンセル トークンをこのメソッドに渡します。
            </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricServiceNotFoundException">
          <para>
            指定した serviceUri に一致するクラスターでサービス インスタンスがない場合、このメソッドは、FabricServiceNotFoundExcepion をスローできます。
            </para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            ServicePartitionKey で指定されたスキームがサービス インスタンスの作成に使用されるスキームと一致しない場合は、FabricException がスローします。
            関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/">エラーと例外</see>詳細についてはします。
            </para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="SetDefault">
      <MemberSignature Language="C#" Value="public static void SetDefault (Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver defaultServiceResolver);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void SetDefault(class Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver defaultServiceResolver) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.SetDefault(Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub SetDefault (defaultServiceResolver As ServicePartitionResolver)" />
      <MemberSignature Language="F#" Value="static member SetDefault : Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver -&gt; unit" Usage="Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.SetDefault defaultServiceResolver" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="defaultServiceResolver" Type="Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" />
      </Parameters>
      <Docs>
        <param name="defaultServiceResolver">新しい既定値</param>
        <summary>
            ServicePartitionResolver 既定値を更新します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>