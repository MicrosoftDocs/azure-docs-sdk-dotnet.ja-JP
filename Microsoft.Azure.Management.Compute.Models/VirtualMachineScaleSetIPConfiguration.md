<Type Name="VirtualMachineScaleSetIPConfiguration" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetIPConfiguration : Microsoft.Azure.Management.Compute.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetIPConfiguration extends Microsoft.Azure.Management.Compute.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetIPConfiguration&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetIPConfiguration = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Compute.Models.SubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            仮想マシン スケール セット ネットワーク プロファイルの IP 構成をについて説明します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetIPConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            VirtualMachineScaleSetIPConfiguration クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetIPConfiguration (string name, string id = null, Microsoft.Azure.Management.Compute.Models.ApiEntityReference subnet = null, Nullable&lt;bool&gt; primary = null, Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetPublicIPAddressConfiguration publicIPAddressConfiguration = null, string privateIPAddressVersion = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; applicationGatewayBackendAddressPools = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; loadBalancerBackendAddressPools = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; loadBalancerInboundNatPools = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string id, class Microsoft.Azure.Management.Compute.Models.ApiEntityReference subnet, valuetype System.Nullable`1&lt;bool&gt; primary, class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetPublicIPAddressConfiguration publicIPAddressConfiguration, string privateIPAddressVersion, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.SubResource&gt; applicationGatewayBackendAddressPools, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.SubResource&gt; loadBalancerBackendAddressPools, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.SubResource&gt; loadBalancerInboundNatPools) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration.#ctor(System.String,System.String,Microsoft.Azure.Management.Compute.Models.ApiEntityReference,System.Nullable{System.Boolean},Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetPublicIPAddressConfiguration,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.SubResource},System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.SubResource},System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.SubResource})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional id As String = null, Optional subnet As ApiEntityReference = null, Optional primary As Nullable(Of Boolean) = null, Optional publicIPAddressConfiguration As VirtualMachineScaleSetPublicIPAddressConfiguration = null, Optional privateIPAddressVersion As String = null, Optional applicationGatewayBackendAddressPools As IList(Of SubResource) = null, Optional loadBalancerBackendAddressPools As IList(Of SubResource) = null, Optional loadBalancerInboundNatPools As IList(Of SubResource) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration : string * string * Microsoft.Azure.Management.Compute.Models.ApiEntityReference * Nullable&lt;bool&gt; * Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetPublicIPAddressConfiguration * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration (name, id, subnet, primary, publicIPAddressConfiguration, privateIPAddressVersion, applicationGatewayBackendAddressPools, loadBalancerBackendAddressPools, loadBalancerInboundNatPools)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="subnet" Type="Microsoft.Azure.Management.Compute.Models.ApiEntityReference" />
        <Parameter Name="primary" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="publicIPAddressConfiguration" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetPublicIPAddressConfiguration" />
        <Parameter Name="privateIPAddressVersion" Type="System.String" />
        <Parameter Name="applicationGatewayBackendAddressPools" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt;" />
        <Parameter Name="loadBalancerBackendAddressPools" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt;" />
        <Parameter Name="loadBalancerInboundNatPools" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt;" />
      </Parameters>
      <Docs>
        <param name="name">IP 構成の名前。</param>
        <param name="id">リソース Id</param>
        <param name="subnet">サブネットの識別子を指定します。</param>
        <param name="primary">バーチャル マシンが 1 つ以上のネットワーク インターフェイスを持つ場合に、プライマリ ネットワーク インターフェイスを指定します。</param>
        <param name="publicIPAddressConfiguration">PublicIPAddressConfiguration です。</param>
        <param name="privateIPAddressVersion">Api-バージョン 2017年-03-30 から使用可能な以降、そのかどうかを特定の ip 構成は、IPv4 または IPv6 です。 既定値は、IPv4 と見なされます。
            使用可能な値が: 'IPv4' および 'IPv6' です。 使用可能な値が含まれます: 'IPv4'、'IPv6'</param>
        <param name="applicationGatewayBackendAddressPools">Application gateway のバックエンド アドレス プールへの参照の配列を指定します。 スケール セットでは、複数のゲートウェイがアプリケーションのバックエンド アドレス プールを参照できます。 複数のスケール セットでは、同じアプリケーション ゲートウェイを使用できません。</param>
        <param name="loadBalancerBackendAddressPools">ロード バランサーのバックエンド アドレス プールへの参照の配列を指定します。 スケール セットでは、1 つのパブリック証明書と 1 つの内部ロード バランサーのバックエンド アドレス プールを参照できます。 複数のスケール セットでは、同じロード バランサーを使用できません。</param>
        <param name="loadBalancerInboundNatPools">着信 Nat プール、ロード バランサーへの参照の配列を指定します。 スケール セットでは、1 つのパブリック証明書と 1 つの内部ロード バランサーの着信 nat プールを参照できます。 複数のスケール セットが同じロード バランサーを使用することはできません。</param>
        <summary>
            VirtualMachineScaleSetIPConfiguration クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationGatewayBackendAddressPools">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; ApplicationGatewayBackendAddressPools { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.SubResource&gt; ApplicationGatewayBackendAddressPools" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration.ApplicationGatewayBackendAddressPools" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationGatewayBackendAddressPools As IList(Of SubResource)" />
      <MemberSignature Language="F#" Value="member this.ApplicationGatewayBackendAddressPools : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration.ApplicationGatewayBackendAddressPools" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.applicationGatewayBackendAddressPools")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、application gateway のバックエンド アドレス プールへの参照の配列を指定します。 スケール セットでは、複数のゲートウェイがアプリケーションのバックエンド アドレス プールを参照できます。 複数のスケール セットでは、同じアプリケーション ゲートウェイを使用できません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadBalancerBackendAddressPools">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; LoadBalancerBackendAddressPools { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.SubResource&gt; LoadBalancerBackendAddressPools" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration.LoadBalancerBackendAddressPools" />
      <MemberSignature Language="VB.NET" Value="Public Property LoadBalancerBackendAddressPools As IList(Of SubResource)" />
      <MemberSignature Language="F#" Value="member this.LoadBalancerBackendAddressPools : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration.LoadBalancerBackendAddressPools" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.loadBalancerBackendAddressPools")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、ロード バランサーのバックエンド アドレス プールへの参照の配列を指定します。 スケール セットでは、1 つのパブリック証明書と 1 つの内部ロード バランサーのバックエンド アドレス プールを参照できます。 複数のスケール セットでは、同じロード バランサーを使用できません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadBalancerInboundNatPools">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; LoadBalancerInboundNatPools { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.SubResource&gt; LoadBalancerInboundNatPools" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration.LoadBalancerInboundNatPools" />
      <MemberSignature Language="VB.NET" Value="Public Property LoadBalancerInboundNatPools As IList(Of SubResource)" />
      <MemberSignature Language="F#" Value="member this.LoadBalancerInboundNatPools : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration.LoadBalancerInboundNatPools" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.loadBalancerInboundNatPools")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、着信 Nat プール、ロード バランサーへの参照の配列を指定します。 スケール セットでは、1 つのパブリック証明書と 1 つの内部ロード バランサーの着信 nat プールを参照できます。 複数のスケール セットが同じロード バランサーを使用することはできません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            取得または IP 構成の名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Primary">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Primary { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Primary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration.Primary" />
      <MemberSignature Language="VB.NET" Value="Public Property Primary As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Primary : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration.Primary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.primary")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、バーチャル マシンが 1 つ以上のネットワーク インターフェイスを持つ場合に、プライマリ ネットワーク インターフェイスを指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrivateIPAddressVersion">
      <MemberSignature Language="C#" Value="public string PrivateIPAddressVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrivateIPAddressVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration.PrivateIPAddressVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property PrivateIPAddressVersion As String" />
      <MemberSignature Language="F#" Value="member this.PrivateIPAddressVersion : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration.PrivateIPAddressVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.privateIPAddressVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定 Api-バージョン 2017年-03-30 から使用可能な以降、特定の ip 構成が IPv4 または IPv6 であるかどうかを表します。
            既定値は、IPv4 と見なされます。  使用可能な値が: 'IPv4' および 'IPv6' です。
            使用可能な値が含まれます: 'IPv4'、'IPv6'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicIPAddressConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetPublicIPAddressConfiguration PublicIPAddressConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetPublicIPAddressConfiguration PublicIPAddressConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration.PublicIPAddressConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property PublicIPAddressConfiguration As VirtualMachineScaleSetPublicIPAddressConfiguration" />
      <MemberSignature Language="F#" Value="member this.PublicIPAddressConfiguration : Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetPublicIPAddressConfiguration with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration.PublicIPAddressConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.publicIPAddressConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetPublicIPAddressConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、publicIPAddressConfiguration を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.ApiEntityReference Subnet { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.ApiEntityReference Subnet" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration.Subnet" />
      <MemberSignature Language="VB.NET" Value="Public Property Subnet As ApiEntityReference" />
      <MemberSignature Language="F#" Value="member this.Subnet : Microsoft.Azure.Management.Compute.Models.ApiEntityReference with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration.Subnet" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.subnet")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.ApiEntityReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、サブネットの識別子を指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="virtualMachineScaleSetIPConfiguration.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>