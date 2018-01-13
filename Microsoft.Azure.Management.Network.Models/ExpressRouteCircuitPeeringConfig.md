<Type Name="ExpressRouteCircuitPeeringConfig" FullName="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig">
  <TypeSignature Language="C#" Value="public class ExpressRouteCircuitPeeringConfig" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExpressRouteCircuitPeeringConfig extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig" />
  <TypeSignature Language="VB.NET" Value="Public Class ExpressRouteCircuitPeeringConfig" />
  <TypeSignature Language="F#" Value="type ExpressRouteCircuitPeeringConfig = class" />
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
            ピアリングの構成を指定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExpressRouteCircuitPeeringConfig ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig.#ctor" />
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
            ExpressRouteCircuitPeeringConfig クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExpressRouteCircuitPeeringConfig (System.Collections.Generic.IList&lt;string&gt; advertisedPublicPrefixes = null, System.Collections.Generic.IList&lt;string&gt; advertisedCommunities = null, string advertisedPublicPrefixesState = null, Nullable&lt;int&gt; legacyMode = null, Nullable&lt;int&gt; customerASN = null, string routingRegistryName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; advertisedPublicPrefixes, class System.Collections.Generic.IList`1&lt;string&gt; advertisedCommunities, string advertisedPublicPrefixesState, valuetype System.Nullable`1&lt;int32&gt; legacyMode, valuetype System.Nullable`1&lt;int32&gt; customerASN, string routingRegistryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig.#ctor(System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String},System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional advertisedPublicPrefixes As IList(Of String) = null, Optional advertisedCommunities As IList(Of String) = null, Optional advertisedPublicPrefixesState As String = null, Optional legacyMode As Nullable(Of Integer) = null, Optional customerASN As Nullable(Of Integer) = null, Optional routingRegistryName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig : System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * string -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig" Usage="new Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig (advertisedPublicPrefixes, advertisedCommunities, advertisedPublicPrefixesState, legacyMode, customerASN, routingRegistryName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="advertisedPublicPrefixes" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="advertisedCommunities" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="advertisedPublicPrefixesState" Type="System.String" />
        <Parameter Name="legacyMode" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customerASN" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="routingRegistryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="advertisedPublicPrefixes">AdvertisedPublicPrefixes の参照です。</param>
        <param name="advertisedCommunities">Bgp ピアリングのコミュニティです。
            Microsoft ピアリング Spepcified</param>
        <param name="advertisedPublicPrefixesState">ピアリング リソースの AdvertisedPublicPrefixState します。 使用可能な値は 'NotConfigured'、'構成'、'構成' および 'ValidationNeeded' です。 使用可能な値が含まれます: 'NotConfigured'、'構成'、'構成'、'ValidationNeeded'</param>
        <param name="legacyMode">ピアリングのレガシ モードです。</param>
        <param name="customerASN">ピアリングの CustomerASN します。</param>
        <param name="routingRegistryName">構成の RoutingRegistryName します。</param>
        <summary>
            ExpressRouteCircuitPeeringConfig クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdvertisedCommunities">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AdvertisedCommunities { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AdvertisedCommunities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig.AdvertisedCommunities" />
      <MemberSignature Language="VB.NET" Value="Public Property AdvertisedCommunities As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AdvertisedCommunities : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig.AdvertisedCommunities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="advertisedCommunities")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または bgp ピアリングのコミュニティを設定します。 Microsoft ピアリング Spepcified
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdvertisedPublicPrefixes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AdvertisedPublicPrefixes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AdvertisedPublicPrefixes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig.AdvertisedPublicPrefixes" />
      <MemberSignature Language="VB.NET" Value="Public Property AdvertisedPublicPrefixes As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AdvertisedPublicPrefixes : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig.AdvertisedPublicPrefixes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="advertisedPublicPrefixes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または AdvertisedPublicPrefixes への参照を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdvertisedPublicPrefixesState">
      <MemberSignature Language="C#" Value="public string AdvertisedPublicPrefixesState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdvertisedPublicPrefixesState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig.AdvertisedPublicPrefixesState" />
      <MemberSignature Language="VB.NET" Value="Public Property AdvertisedPublicPrefixesState As String" />
      <MemberSignature Language="F#" Value="member this.AdvertisedPublicPrefixesState : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig.AdvertisedPublicPrefixesState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="advertisedPublicPrefixesState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはピアリング リソースの advertisedPublicPrefixState を設定します。
            使用可能な値は 'NotConfigured'、'構成'、'構成' および 'ValidationNeeded' です。 使用可能な値が含まれます: 'NotConfigured'、'構成'、'構成'、'ValidationNeeded'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomerASN">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; CustomerASN { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; CustomerASN" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig.CustomerASN" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomerASN As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.CustomerASN : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig.CustomerASN" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="customerASN")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはピアリングの CustomerASN を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LegacyMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LegacyMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LegacyMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig.LegacyMode" />
      <MemberSignature Language="VB.NET" Value="Public Property LegacyMode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LegacyMode : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig.LegacyMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="legacyMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはピアリングのレガシ モードを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RoutingRegistryName">
      <MemberSignature Language="C#" Value="public string RoutingRegistryName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RoutingRegistryName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig.RoutingRegistryName" />
      <MemberSignature Language="VB.NET" Value="Public Property RoutingRegistryName As String" />
      <MemberSignature Language="F#" Value="member this.RoutingRegistryName : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig.RoutingRegistryName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="routingRegistryName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の RoutingRegistryName を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>