<Type Name="PacketCaptureFilter" FullName="Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter">
  <TypeSignature Language="C#" Value="public class PacketCaptureFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PacketCaptureFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class PacketCaptureFilter" />
  <TypeSignature Language="F#" Value="type PacketCaptureFilter = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            パケットのキャプチャ要求に適用されるフィルターです。 複数のフィルターを適用できます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PacketCaptureFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            PacketCaptureFilter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PacketCaptureFilter (string protocol = null, string localIPAddress = null, string remoteIPAddress = null, string localPort = null, string remotePort = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string protocol, string localIPAddress, string remoteIPAddress, string localPort, string remotePort) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional protocol As String = null, Optional localIPAddress As String = null, Optional remoteIPAddress As String = null, Optional localPort As String = null, Optional remotePort As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter : string * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter (protocol, localIPAddress, remoteIPAddress, localPort, remotePort)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="protocol" Type="System.String" />
        <Parameter Name="localIPAddress" Type="System.String" />
        <Parameter Name="remoteIPAddress" Type="System.String" />
        <Parameter Name="localPort" Type="System.String" />
        <Parameter Name="remotePort" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="protocol">フィルターが適用するプロトコル。 使用可能な値が含まれます: 'TCP'、'UDP'、'Any'</param>
        <param name="localIPAddress">フィルター選択するローカル IP アドレス。
            Notation:「127.0.0.1」の 1 つのアドレスのエントリ。
            「127.0.0.1-127.0.0.255」の範囲です。 "127.0.0.1;127.0.0.5"? 複数のエントリ。 複数の範囲は現在サポートされていません。 現在サポートされていない複数のエントリを持つ範囲が混在します。 既定の null を = です。</param>
        <param name="remoteIPAddress">フィルター選択するローカル IP アドレス。
            Notation:「127.0.0.1」の 1 つのアドレスのエントリ。
            「127.0.0.1-127.0.0.255」の範囲です。 「127.0.0.1;127.0.0.5;」の複数のエントリ。 複数の範囲は現在サポートされていません。 現在サポートされていない複数のエントリを持つ範囲が混在します。 既定の null を = です。</param>
        <param name="localPort">フィルターが適用にローカル ポートです。 表記法: 単一のポートのエントリを示す「80」です"。80-85"の範囲です。 「80; 443;」の複数のエントリ。 複数の範囲は現在サポートされていません。 現在サポートされていない複数のエントリを持つ範囲が混在します。 既定の null を = です。</param>
        <param name="remotePort">フィルター選択されるリモート ポート。 表記法: 単一のポートのエントリを示す「80」です"。80-85"の範囲です。 「80; 443;」の複数のエントリ。 複数の範囲は現在サポートされていません。 現在サポートされていない複数のエントリを持つ範囲が混在します。 既定の null を = です。</param>
        <summary>
            PacketCaptureFilter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalIPAddress">
      <MemberSignature Language="C#" Value="public string LocalIPAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LocalIPAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter.LocalIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property LocalIPAddress As String" />
      <MemberSignature Language="F#" Value="member this.LocalIPAddress : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter.LocalIPAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="localIPAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはにフィルターが適用するローカル IP アドレスを設定します。 Notation:「127.0.0.1」の 1 つのアドレスのエントリ。 「127.0.0.1-127.0.0.255」の範囲です。 "127.0.0.1;127.0.0.5"? 複数のエントリ。 複数の範囲は現在サポートされていません。 現在サポートされていない複数のエントリを持つ範囲が混在します。 既定の null を = です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalPort">
      <MemberSignature Language="C#" Value="public string LocalPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LocalPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter.LocalPort" />
      <MemberSignature Language="VB.NET" Value="Public Property LocalPort As String" />
      <MemberSignature Language="F#" Value="member this.LocalPort : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter.LocalPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="localPort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはにフィルターが適用にローカル ポートを設定します。 表記法: 単一のポートのエントリを示す「80」です"。80-85"の範囲です。 「80; 443;」の複数のエントリ。 複数の範囲は現在サポートされていません。 現在サポートされていない複数のエントリを持つ範囲が混在します。 既定の null を = です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public string Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As String" />
      <MemberSignature Language="F#" Value="member this.Protocol : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter.Protocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="protocol")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはにフィルターが適用するプロトコルを設定します。 使用可能な値が含まれます: 'TCP'、'UDP'、'Any'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteIPAddress">
      <MemberSignature Language="C#" Value="public string RemoteIPAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RemoteIPAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter.RemoteIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property RemoteIPAddress As String" />
      <MemberSignature Language="F#" Value="member this.RemoteIPAddress : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter.RemoteIPAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="remoteIPAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはにフィルターが適用するローカル IP アドレスを設定します。 Notation:「127.0.0.1」の 1 つのアドレスのエントリ。 「127.0.0.1-127.0.0.255」の範囲です。 「127.0.0.1;127.0.0.5;」の複数のエントリ。 複数の範囲は現在サポートされていません。 現在サポートされていない複数のエントリを持つ範囲が混在します。 既定の null を = です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemotePort">
      <MemberSignature Language="C#" Value="public string RemotePort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RemotePort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter.RemotePort" />
      <MemberSignature Language="VB.NET" Value="Public Property RemotePort As String" />
      <MemberSignature Language="F#" Value="member this.RemotePort : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter.RemotePort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="remotePort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはでフィルター選択されるリモートのポートを設定します。 表記法: 単一のポートのエントリを示す「80」です"。80-85"の範囲です。 「80; 443;」の複数のエントリ。 複数の範囲は現在サポートされていません。 現在サポートされていない複数のエントリを持つ範囲が混在します。 既定の null を = です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>