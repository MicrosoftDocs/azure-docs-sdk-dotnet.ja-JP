<Type Name="WcfCommunicationClientFactory&lt;TServiceContract&gt;" FullName="Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory&lt;TServiceContract&gt;">
  <TypeSignature Language="C#" Value="public class WcfCommunicationClientFactory&lt;TServiceContract&gt; : Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase&lt;Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;TServiceContract&gt;&gt; where TServiceContract : class" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WcfCommunicationClientFactory`1&lt;class TServiceContract&gt; extends Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1&lt;class Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient`1&lt;!TServiceContract&gt;&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory`1" />
  <TypeSignature Language="VB.NET" Value="Public Class WcfCommunicationClientFactory(Of TServiceContract)&#xA;Inherits CommunicationClientFactoryBase(Of WcfCommunicationClient(Of TServiceContract))" />
  <TypeSignature Language="F#" Value="type WcfCommunicationClientFactory&lt;'ServiceContract (requires 'ServiceContract : null)&gt; = class&#xA;    inherit CommunicationClientFactoryBase&lt;WcfCommunicationClient&lt;'ServiceContract&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TServiceContract">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase&lt;Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;TServiceContract&gt;&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;TServiceContract&gt;</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="TServiceContract">WCF ベースのサービス コントラクト</typeparam>
    <summary>
            <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1" /> Windows Communication Foundation を使用して作成する<see cref="T:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient`1" />を使用しているステートレスおよびステートフルなサービスと通信する<see cref="T:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1" />です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfCommunicationClientFactory (System.ServiceModel.Channels.Binding clientBinding = null, System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; exceptionHandlers = null, Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver servicePartitionResolver = null, string traceId = null, object callback = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.ServiceModel.Channels.Binding clientBinding, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; exceptionHandlers, class Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver servicePartitionResolver, string traceId, object callback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory`1.#ctor(System.ServiceModel.Channels.Binding,System.Collections.Generic.IEnumerable{Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler},Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver,System.String,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional clientBinding As Binding = null, Optional exceptionHandlers As IEnumerable(Of IExceptionHandler) = null, Optional servicePartitionResolver As IServicePartitionResolver = null, Optional traceId As String = null, Optional callback As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory&lt;'ServiceContract (requires 'ServiceContract : null)&gt; : System.ServiceModel.Channels.Binding * seq&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; * Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver * string * obj -&gt; Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory&lt;'ServiceContract (requires 'ServiceContract : null)&gt;" Usage="new Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory&lt;'ServiceContract (requires 'ServiceContract : null)&gt; (clientBinding, exceptionHandlers, servicePartitionResolver, traceId, callback)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientBinding" Type="System.ServiceModel.Channels.Binding" />
        <Parameter Name="exceptionHandlers" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt;" />
        <Parameter Name="servicePartitionResolver" Type="Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver" />
        <Parameter Name="traceId" Type="System.String" />
        <Parameter Name="callback" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="clientBinding">
                クライアントに使用する WCF バインドします。 クライアントのバインディングが指定されていないか、null、既定のクライアントのバインドを作成を使用して場合<see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpClientBinding(System.Int64,System.TimeSpan,System.TimeSpan)" />を作成する方法、<see cref="T:System.ServiceModel.NetTcpBinding" />セキュリティなし。
                </param>
        <param name="exceptionHandlers">
                サービスと通信中に発生した例外を処理する例外ハンドラーです。
            </param>
        <param name="servicePartitionResolver">
                サービス エンドポイントを解決するのにはサービス パーティション リゾルバー。 既定のサービス パーティション リゾルバーがによって返される指定しない場合、<see cref="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.GetDefault" />を使用します。
                </param>
        <param name="traceId">
                このコンポーネントからのトレースを診断で使用する id。
            </param>
        <param name="callback">
                サービスからのコールバックを受信するコールバック クライアント。
            </param>
        <summary>
            WCF を使用して、サービスと通信するクライアントを作成するファクトリを構築します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbortClient">
      <MemberSignature Language="C#" Value="protected override void AbortClient (Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;TServiceContract&gt; client);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void AbortClient(class Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient`1&lt;!TServiceContract&gt; client) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory`1.AbortClient(Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient{`0})" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub AbortClient (client As WcfCommunicationClient(Of TServiceContract))" />
      <MemberSignature Language="F#" Value="override this.AbortClient : Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;'ServiceContract (requires 'ServiceContract : null)&gt; -&gt; unit" Usage="wcfCommunicationClientFactory.AbortClient client" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;TServiceContract&gt;" />
      </Parameters>
      <Docs>
        <param name="client">クライアントの通信</param>
        <summary>
            指定したクライアントを中止します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateClientAsync">
      <MemberSignature Language="C#" Value="protected override System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;TServiceContract&gt;&gt; CreateClientAsync (string endpoint, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient`1&lt;!TServiceContract&gt;&gt; CreateClientAsync(string endpoint, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory`1.CreateClientAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.CreateClientAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;'ServiceContract&gt;&gt;" Usage="wcfCommunicationClientFactory.CreateClientAsync (endpoint, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory`1/&lt;CreateClientAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;TServiceContract&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoint" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="endpoint">サービスがリッスンしているエンドポイント アドレス</param>
        <param name="cancellationToken">キャンセル トークン</param>
        <summary>
            指定したエンドポイント アドレスの通信のクライアントを作成します。
            </summary>
        <returns>作成された通信のクライアント</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateWcfCommunicationClient">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;TServiceContract&gt; CreateWcfCommunicationClient (TServiceContract channel);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient`1&lt;!TServiceContract&gt; CreateWcfCommunicationClient(!TServiceContract channel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory`1.CreateWcfCommunicationClient(`0)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function CreateWcfCommunicationClient (channel As TServiceContract) As WcfCommunicationClient(Of TServiceContract)" />
      <MemberSignature Language="F#" Value="abstract member CreateWcfCommunicationClient : 'ServiceContract -&gt; Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;'ServiceContract (requires 'ServiceContract : null)&gt;&#xA;override this.CreateWcfCommunicationClient : 'ServiceContract -&gt; Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;'ServiceContract (requires 'ServiceContract : null)&gt;" Usage="wcfCommunicationClientFactory.CreateWcfCommunicationClient channel" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;TServiceContract&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="channel" Type="TServiceContract" />
      </Parameters>
      <Docs>
        <param name="channel">WCF チャネルをサービス コントラクトに基づいています。</param>
        <summary>
            指定されたチャネル経由で通信するために WCF 通信のクライアントを作成します。
            </summary>
        <returns>作成された通信のクライアント</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateClient">
      <MemberSignature Language="C#" Value="protected override bool ValidateClient (Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;TServiceContract&gt; client);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool ValidateClient(class Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient`1&lt;!TServiceContract&gt; client) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory`1.ValidateClient(Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient{`0})" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function ValidateClient (client As WcfCommunicationClient(Of TServiceContract)) As Boolean" />
      <MemberSignature Language="F#" Value="override this.ValidateClient : Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;'ServiceContract (requires 'ServiceContract : null)&gt; -&gt; bool" Usage="wcfCommunicationClientFactory.ValidateClient client" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;TServiceContract&gt;" />
      </Parameters>
      <Docs>
        <param name="client">WCF の通信用クライアント</param>
        <summary>
            クライアントがまだ有効な場合に true を返します。 接続指向トランスポートでは、クライアントがサービスに接続していないことを示すために、このメソッドを使用できます。
            </summary>
        <returns>クライアントは、有効な場合は false をそれ以外の場合は true</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateClient">
      <MemberSignature Language="C#" Value="protected override bool ValidateClient (string endpoint, Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;TServiceContract&gt; client);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool ValidateClient(string endpoint, class Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient`1&lt;!TServiceContract&gt; client) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory`1.ValidateClient(System.String,Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient{`0})" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function ValidateClient (endpoint As String, client As WcfCommunicationClient(Of TServiceContract)) As Boolean" />
      <MemberSignature Language="F#" Value="override this.ValidateClient : string * Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;'ServiceContract (requires 'ServiceContract : null)&gt; -&gt; bool" Usage="wcfCommunicationClientFactory.ValidateClient (endpoint, client)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoint" Type="System.String" />
        <Parameter Name="client" Type="Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClient&lt;TServiceContract&gt;" />
      </Parameters>
      <Docs>
        <param name="endpoint">エンドポイントの文字列</param>
        <param name="client">WCF の通信用クライアント</param>
        <summary>
            クライアントがまだ有効であり、パラメーターで指定されたエンドポイントに接続されている場合に true を返します。
            </summary>
        <returns>クライアントは、有効な場合は false をそれ以外の場合は true</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>