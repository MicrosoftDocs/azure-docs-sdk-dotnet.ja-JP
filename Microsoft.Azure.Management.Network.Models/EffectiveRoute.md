<Type Name="EffectiveRoute" FullName="Microsoft.Azure.Management.Network.Models.EffectiveRoute">
  <TypeSignature Language="C#" Value="public class EffectiveRoute" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EffectiveRoute extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.EffectiveRoute" />
  <TypeSignature Language="VB.NET" Value="Public Class EffectiveRoute" />
  <TypeSignature Language="F#" Value="type EffectiveRoute = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            有効なルート
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EffectiveRoute ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.EffectiveRoute.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            EffectiveRoute クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EffectiveRoute (string name = null, string source = null, string state = null, System.Collections.Generic.IList&lt;string&gt; addressPrefix = null, System.Collections.Generic.IList&lt;string&gt; nextHopIpAddress = null, string nextHopType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string source, string state, class System.Collections.Generic.IList`1&lt;string&gt; addressPrefix, class System.Collections.Generic.IList`1&lt;string&gt; nextHopIpAddress, string nextHopType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.EffectiveRoute.#ctor(System.String,System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional source As String = null, Optional state As String = null, Optional addressPrefix As IList(Of String) = null, Optional nextHopIpAddress As IList(Of String) = null, Optional nextHopType As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.EffectiveRoute : string * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; * string -&gt; Microsoft.Azure.Management.Network.Models.EffectiveRoute" Usage="new Microsoft.Azure.Management.Network.Models.EffectiveRoute (name, source, state, addressPrefix, nextHopIpAddress, nextHopType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="source" Type="System.String" />
        <Parameter Name="state" Type="System.String" />
        <Parameter Name="addressPrefix" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="nextHopIpAddress" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="nextHopType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">ユーザーの名前には、ルートが定義されています。 これは省略可能です。</param>
        <param name="source">ルートを作成したとします。 使用可能な値が: 'Unknown'、'User'、'VirtualNetworkGateway' および 'Default' です。 使用可能な値が含まれます: 'Unknown'、'User'、'VirtualNetworkGateway'、'Default'</param>
        <param name="state">有効なルートの値。 使用可能な値が: 'Active'、'無効' です。 使用可能な値が含まれます: 'Active'、'無効'</param>
        <param name="addressPrefix">CIDR 表記法で効果的なルートのアドレス プレフィックス。</param>
        <param name="nextHopIpAddress">有効なルートの次のホップの IP アドレス。</param>
        <param name="nextHopType">パケットの送信先となる Azure ホップの種類。 使用可能な値が: 'VirtualNetworkGateway'、'VnetLocal'、'Internet'、'VirtualAppliance' および 'None' です。 使用可能な値が含まれます: 'VirtualNetworkGateway'、'VnetLocal'、'Internet'、'VirtualAppliance'、'None'</param>
        <summary>
            EffectiveRoute クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddressPrefix">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AddressPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AddressPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveRoute.AddressPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property AddressPrefix As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AddressPrefix : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveRoute.AddressPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="addressPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または CIDR 表記法で効果的なルートのアドレス プレフィックスを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveRoute.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveRoute.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはユーザー定義ルートの名前を設定します。 これは省略可能です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextHopIpAddress">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; NextHopIpAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; NextHopIpAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveRoute.NextHopIpAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property NextHopIpAddress As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.NextHopIpAddress : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveRoute.NextHopIpAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nextHopIpAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または有効なルートの次のホップの IP アドレスを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextHopType">
      <MemberSignature Language="C#" Value="public string NextHopType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextHopType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveRoute.NextHopType" />
      <MemberSignature Language="VB.NET" Value="Public Property NextHopType As String" />
      <MemberSignature Language="F#" Value="member this.NextHopType : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveRoute.NextHopType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nextHopType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはにパケットを送信するか Azure ホップの種類を設定します。
            使用可能な値が: 'VirtualNetworkGateway'、'VnetLocal'、'Internet'、'VirtualAppliance' および 'None' です。 使用可能な値が含まれます: 'VirtualNetworkGateway'、'VnetLocal'、'Internet'、'VirtualAppliance'、'None'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Source">
      <MemberSignature Language="C#" Value="public string Source { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Source" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveRoute.Source" />
      <MemberSignature Language="VB.NET" Value="Public Property Source As String" />
      <MemberSignature Language="F#" Value="member this.Source : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveRoute.Source" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="source")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはルートを作成したユーザーを設定します。 使用可能な値が: 'Unknown'、'User'、'VirtualNetworkGateway' および 'Default' です。 使用可能な値が含まれます: 'Unknown'、'User'、'VirtualNetworkGateway'、'Default'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveRoute.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveRoute.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または有効なルートの値を設定します。 使用可能な値が: 'Active'、'無効' です。 使用可能な値が含まれます: 'Active'、'無効'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>