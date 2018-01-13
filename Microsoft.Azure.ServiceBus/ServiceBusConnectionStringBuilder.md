<Type Name="ServiceBusConnectionStringBuilder" FullName="Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder">
  <TypeSignature Language="C#" Value="public class ServiceBusConnectionStringBuilder" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceBusConnectionStringBuilder extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceBusConnectionStringBuilder" />
  <TypeSignature Language="F#" Value="type ServiceBusConnectionStringBuilder = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Service Bus の接続文字列を生成するために使用します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceBusConnectionStringBuilder ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            新しいインスタンスを作成します。<see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceBusConnectionStringBuilder (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (connectionString As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder : string -&gt; Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" Usage="new Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder connectionString" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">名前空間またはエンティティの接続文字列。</param>
        <summary>
            新しい <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" /> をインスタンス化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceBusConnectionStringBuilder (string endpoint, string entityPath, string sharedAccessSignature);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string endpoint, string entityPath, string sharedAccessSignature) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (endpoint As String, entityPath As String, sharedAccessSignature As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder : string * string * string -&gt; Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" Usage="new Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder (endpoint, entityPath, sharedAccessSignature)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endpoint" Type="System.String" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="sharedAccessSignature" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpoint">完全修飾エンドポイントです。</param>
        <param name="entityPath">To be added.</param>
        <param name="sharedAccessSignature">To be added.</param>
        <summary>
            新しい <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" /> をインスタンス化します。
            </summary>
        <remarks>To be added.</remarks>
        <example>
          <code>
            var connectionStringBuilder 新しい ServiceBusConnectionStringBuilder ("contoso.servicebus.windows.net"、"myQueue"、"{... を =SAS トークン...}") です。
                </code>
        </example>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceBusConnectionStringBuilder (string endpoint, string entityPath, string sharedAccessSignature, Microsoft.Azure.ServiceBus.TransportType transportType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string endpoint, string entityPath, string sharedAccessSignature, valuetype Microsoft.Azure.ServiceBus.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.#ctor(System.String,System.String,System.String,Microsoft.Azure.ServiceBus.TransportType)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder : string * string * string * Microsoft.Azure.ServiceBus.TransportType -&gt; Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" Usage="new Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder (endpoint, entityPath, sharedAccessSignature, transportType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endpoint" Type="System.String" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="sharedAccessSignature" Type="System.String" />
        <Parameter Name="transportType" Type="Microsoft.Azure.ServiceBus.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpoint">完全修飾エンドポイントです。</param>
        <param name="entityPath">To be added.</param>
        <param name="sharedAccessSignature">To be added.</param>
        <param name="transportType">To be added.</param>
        <summary>
            新しい <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" /> をインスタンス化します。
            </summary>
        <remarks>To be added.</remarks>
        <example>
          <code>
            var connectionStringBuilder 新しい ServiceBusConnectionStringBuilder ("contoso.servicebus.windows.net"、"myQueue"、"{... を =SAS トークン...}", TransportType.Amqp) です。
                </code>
        </example>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceBusConnectionStringBuilder (string endpoint, string entityPath, string sharedAccessKeyName, string sharedAccessKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string endpoint, string entityPath, string sharedAccessKeyName, string sharedAccessKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (endpoint As String, entityPath As String, sharedAccessKeyName As String, sharedAccessKey As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder : string * string * string * string -&gt; Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" Usage="new Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder (endpoint, entityPath, sharedAccessKeyName, sharedAccessKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="sharedAccessKeyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpoint">完全修飾エンドポイントです。</param>
        <param name="entityPath">エンティティへのパス。</param>
        <param name="sharedAccessKeyName">アクセス キーの名前を共有します。</param>
        <param name="sharedAccessKey">共有アクセス キー。</param>
        <summary>
            新しい <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" /> をインスタンス化します。
            </summary>
        <remarks>To be added.</remarks>
        <example>
          <code>
            var connectionStringBuilder = 新しい ServiceBusConnectionStringBuilder ("contoso.servicebus.windows.net"、"myQueue"、"RootManageSharedAccessKey"、"&amp;lt; sharedAccessKey&amp;gt;) です。
                </code>
        </example>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceBusConnectionStringBuilder (string endpoint, string entityPath, string sharedAccessKeyName, string sharedAccessKey, Microsoft.Azure.ServiceBus.TransportType transportType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string endpoint, string entityPath, string sharedAccessKeyName, string sharedAccessKey, valuetype Microsoft.Azure.ServiceBus.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.#ctor(System.String,System.String,System.String,System.String,Microsoft.Azure.ServiceBus.TransportType)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder : string * string * string * string * Microsoft.Azure.ServiceBus.TransportType -&gt; Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" Usage="new Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder (endpoint, entityPath, sharedAccessKeyName, sharedAccessKey, transportType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endpoint" Type="System.String" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="sharedAccessKeyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
        <Parameter Name="transportType" Type="Microsoft.Azure.ServiceBus.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpoint">完全修飾エンドポイントです。</param>
        <param name="entityPath">To be added.</param>
        <param name="sharedAccessKeyName">To be added.</param>
        <param name="sharedAccessKey">To be added.</param>
        <param name="transportType">To be added.</param>
        <summary>
            新しい <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" /> をインスタンス化します。
            </summary>
        <remarks>To be added.</remarks>
        <example>
          <code>
            var connectionStringBuilder = 新しい ServiceBusConnectionStringBuilder ("contoso.servicebus.windows.net"、"myQueue"、"RootManageSharedAccessKey"、"&amp;lt; sharedAccessKey&amp;gt;、TransportType.Amqp) です。
                </code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="Endpoint">
      <MemberSignature Language="C#" Value="public string Endpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Endpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.Endpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property Endpoint As String" />
      <MemberSignature Language="F#" Value="member this.Endpoint : string with get, set" Usage="Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.Endpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            エンドポイントの完全修飾ドメイン名です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <example>
          <code>これ。エンドポイント contoso.servicebus.windows.net を =</code>
        </example>
        <exception cref="T:System.ArgumentException">エンドポイントは、完全修飾エンドポイントではない場合にスローされます。</exception>
        <exception cref="T:System.UriFormatException">ホスト名を解析できない場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="EntityPath">
      <MemberSignature Language="C#" Value="public string EntityPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EntityPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.EntityPath" />
      <MemberSignature Language="VB.NET" Value="Public Property EntityPath As String" />
      <MemberSignature Language="F#" Value="member this.EntityPath : string with get, set" Usage="Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.EntityPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            接続文字列からエンティティ path の値を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEntityConnectionString">
      <MemberSignature Language="C#" Value="public string GetEntityConnectionString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetEntityConnectionString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.GetEntityConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEntityConnectionString () As String" />
      <MemberSignature Language="F#" Value="member this.GetEntityConnectionString : unit -&gt; string" Usage="serviceBusConnectionStringBuilder.GetEntityConnectionString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            指定された ServiceBus エンティティへの接続に使用できる相互操作可能な接続文字列を返します
            </summary>
        <returns>エンティティ接続文字列</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNamespaceConnectionString">
      <MemberSignature Language="C#" Value="public string GetNamespaceConnectionString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetNamespaceConnectionString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.GetNamespaceConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNamespaceConnectionString () As String" />
      <MemberSignature Language="F#" Value="member this.GetNamespaceConnectionString : unit -&gt; string" Usage="serviceBusConnectionStringBuilder.GetNamespaceConnectionString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            ServiceBus Namespace への接続に使用できる相互操作可能な接続文字列を返します
            </summary>
        <returns>Namespace 接続文字列</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SasKey">
      <MemberSignature Language="C#" Value="public string SasKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SasKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.SasKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SasKey As String" />
      <MemberSignature Language="F#" Value="member this.SasKey : string with get, set" Usage="Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.SasKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            接続文字列からの共有アクセス ポリシー キーの値を取得します。
            </summary>
        <value>共有アクセス署名キー</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SasKeyName">
      <MemberSignature Language="C#" Value="public string SasKeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SasKeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.SasKeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property SasKeyName As String" />
      <MemberSignature Language="F#" Value="member this.SasKeyName : string with get, set" Usage="Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.SasKeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            接続文字列から、共有アクセス ポリシーの所有者名を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SasToken">
      <MemberSignature Language="C#" Value="public string SasToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SasToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.SasToken" />
      <MemberSignature Language="VB.NET" Value="Public Property SasToken As String" />
      <MemberSignature Language="F#" Value="member this.SasToken : string with get, set" Usage="Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.SasToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            接続文字列から、共有アクセス署名トークンを取得します。
            </summary>
        <value>共有アクセス署名トークン</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="serviceBusConnectionStringBuilder.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            ServiceBus Namespace への接続に使用できる相互操作可能な接続文字列を返します
            </summary>
        <returns>接続文字列</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransportType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.ServiceBus.TransportType TransportType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.ServiceBus.TransportType TransportType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.TransportType" />
      <MemberSignature Language="VB.NET" Value="Public Property TransportType As TransportType" />
      <MemberSignature Language="F#" Value="member this.TransportType : Microsoft.Azure.ServiceBus.TransportType with get, set" Usage="Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder.TransportType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.TransportType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            接続文字列から、トランスポートの種類を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>