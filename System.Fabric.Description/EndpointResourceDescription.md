<Type Name="EndpointResourceDescription" FullName="System.Fabric.Description.EndpointResourceDescription">
  <TypeSignature Language="C#" Value="public sealed class EndpointResourceDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit EndpointResourceDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.EndpointResourceDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class EndpointResourceDescription" />
  <TypeSignature Language="F#" Value="type EndpointResourceDescription = class" />
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
      <para>Endpoint リソースをについて説明します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EndpointResourceDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.EndpointResourceDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Description.EndpointResourceDescription" /> の新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Certificate">
      <MemberSignature Language="C#" Value="public string Certificate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Certificate" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.EndpointResourceDescription.Certificate" />
      <MemberSignature Language="VB.NET" Value="Public Property Certificate As String" />
      <MemberSignature Language="F#" Value="member this.Certificate : string with get, set" Usage="System.Fabric.Description.EndpointResourceDescription.Certificate" />
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
          <para>使用しないでください。 このプロパティはサポートされていません。</para>
        </summary>
        <value>
          <para><see cref="T:System.String" /> を返します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageName">
      <MemberSignature Language="C#" Value="public string CodePackageName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CodePackageName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.EndpointResourceDescription.CodePackageName" />
      <MemberSignature Language="VB.NET" Value="Public Property CodePackageName As String" />
      <MemberSignature Language="F#" Value="member this.CodePackageName : string with get, set" Usage="System.Fabric.Description.EndpointResourceDescription.CodePackageName" />
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
          <para>
            サービス マニフェスト内でエンドポイント リソースの CodePackageRef 属性で指定されているコード パッケージの名前を取得します。
            </para>
        </summary>
        <value>
          <para><see cref="T:System.String" /> を返します。</para>
        </value>
        <remarks>
            サービス マニフェストのエンドポイント リソースの CodePackageRef 属性が指定されていない場合、その値は空の文字列です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EndpointType">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.EndpointType EndpointType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Description.EndpointType EndpointType" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.EndpointResourceDescription.EndpointType" />
      <MemberSignature Language="VB.NET" Value="Public Property EndpointType As EndpointType" />
      <MemberSignature Language="F#" Value="member this.EndpointType : System.Fabric.Description.EndpointType with get, set" Usage="System.Fabric.Description.EndpointResourceDescription.EndpointType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.EndpointType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>エンドポイントの種類を取得します。</para>
        </summary>
        <value>
          <para>エンドポイントの型。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpAddressOrFqdn">
      <MemberSignature Language="C#" Value="public string IpAddressOrFqdn { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IpAddressOrFqdn" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.EndpointResourceDescription.IpAddressOrFqdn" />
      <MemberSignature Language="VB.NET" Value="Public Property IpAddressOrFqdn As String" />
      <MemberSignature Language="F#" Value="member this.IpAddressOrFqdn : string with get, set" Usage="System.Fabric.Description.EndpointResourceDescription.IpAddressOrFqdn" />
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
          <para>
            このエンドポイントのリソースに関連付けられている IP アドレスを取得します。
            </para>
        </summary>
        <value>
          <para>このエンドポイントのリソースに関連付けられている彼は IP アドレスを返します。</para>
        </value>
        <remarks>
          <para>
            サービス マニフェストで参照されるコード パッケージ エンドポイント リソースの CodePackageRef 属性が指定されていた場合<see cref="P:System.Fabric.Description.EndpointResourceDescription.CodePackageName" />ネットワークの設定を明示的な IP アドレスの割り当て、その値は、このコード パッケージに割り当てられた IP アドレスを指定する必要があります。Service Fabric ランタイム。 それ以外の場合は、その値は、IP アドレス (FQDN) のサービスが実行されているコンピューターです。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.EndpointResourceDescription.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="System.Fabric.Description.EndpointResourceDescription.Name" />
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
          <para>エンドポイントの名前を取得または設定します。</para>
        </summary>
        <value>
          <para>エンドポイントの名前。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PathSuffix">
      <MemberSignature Language="C#" Value="public string PathSuffix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PathSuffix" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.EndpointResourceDescription.PathSuffix" />
      <MemberSignature Language="VB.NET" Value="Public Property PathSuffix As String" />
      <MemberSignature Language="F#" Value="member this.PathSuffix : string with get, set" Usage="System.Fabric.Description.EndpointResourceDescription.PathSuffix" />
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
          <para>エンドポイントのパスのサフィックスを取得します。</para>
        </summary>
        <value>
          <para>/Myapp1 のようなエンドポイントのパスのサフィックス。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Port">
      <MemberSignature Language="C#" Value="public int Port { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Port" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.EndpointResourceDescription.Port" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Port As Integer" />
      <MemberSignature Language="F#" Value="member this.Port : int" Usage="System.Fabric.Description.EndpointResourceDescription.Port" />
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
          <para>このエンドポイントに割り当てられているポートを取得します。</para>
        </summary>
        <value>
          <para>このエンドポイントに割り当てられるポートです。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.EndpointProtocol Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Description.EndpointProtocol Protocol" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.EndpointResourceDescription.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As EndpointProtocol" />
      <MemberSignature Language="F#" Value="member this.Protocol : System.Fabric.Description.EndpointProtocol with get, set" Usage="System.Fabric.Description.EndpointResourceDescription.Protocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.EndpointProtocol</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>このエンドポイントによって使用されるプロトコルを取得します。</para>
        </summary>
        <value>
          <para>このエンドポイントによって使用されるプロトコル。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UriScheme">
      <MemberSignature Language="C#" Value="public string UriScheme { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UriScheme" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.EndpointResourceDescription.UriScheme" />
      <MemberSignature Language="VB.NET" Value="Public Property UriScheme As String" />
      <MemberSignature Language="F#" Value="member this.UriScheme : string with get, set" Usage="System.Fabric.Description.EndpointResourceDescription.UriScheme" />
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
          <para>エンドポイントの Uri スキームを取得します。</para>
        </summary>
        <value>
          <para>Http、https、ftp のようなエンドポイントの uri スキーム。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>