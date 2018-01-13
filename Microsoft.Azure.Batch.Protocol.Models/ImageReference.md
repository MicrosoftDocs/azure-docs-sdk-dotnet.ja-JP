<Type Name="ImageReference" FullName="Microsoft.Azure.Batch.Protocol.Models.ImageReference">
  <TypeSignature Language="C#" Value="public class ImageReference" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ImageReference extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ImageReference" />
  <TypeSignature Language="VB.NET" Value="Public Class ImageReference" />
  <TypeSignature Language="F#" Value="type ImageReference = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Azure の仮想マシンの Marketplace イメージまたはカスタムの Azure の仮想マシン イメージへの参照。 Azure Batch によって検証 Azure Marketplace イメージのすべての参照の一覧を取得するには、'リスト ノード エージェント Sku' の操作を参照してください。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ImageReference.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ImageReference クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageReference (string publisher = null, string offer = null, string sku = null, string version = null, string virtualMachineImageId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string publisher, string offer, string sku, string version, string virtualMachineImageId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ImageReference.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional publisher As String = null, Optional offer As String = null, Optional sku As String = null, Optional version As String = null, Optional virtualMachineImageId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.ImageReference : string * string * string * string * string -&gt; Microsoft.Azure.Batch.Protocol.Models.ImageReference" Usage="new Microsoft.Azure.Batch.Protocol.Models.ImageReference (publisher, offer, sku, version, virtualMachineImageId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="publisher" Type="System.String" />
        <Parameter Name="offer" Type="System.String" />
        <Parameter Name="sku" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="virtualMachineImageId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="publisher">Azure の仮想マシンの Marketplace イメージのパブリッシャーです。</param>
        <param name="offer">Azure の仮想マシンの Marketplace イメージのオファーの種類。</param>
        <param name="sku">Azure の仮想マシンの Marketplace イメージの SKU。</param>
        <param name="version">Azure の仮想マシンの Marketplace イメージのバージョン。</param>
        <param name="virtualMachineImageId">バーチャル マシンのイメージを ARM リソース識別子です。 このカスタム イメージを使用して、プールのノードが作成されますが計算されます。 これは、フォーム/subscriptions/{subscriptionId}/resourceGroups/{resourceGroup}/providers/Microsoft.Compute/images/{imageName の}</param>
        <summary>
            ImageReference クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Offer">
      <MemberSignature Language="C#" Value="public string Offer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Offer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ImageReference.Offer" />
      <MemberSignature Language="VB.NET" Value="Public Property Offer As String" />
      <MemberSignature Language="F#" Value="member this.Offer : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ImageReference.Offer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="offer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure の仮想マシンの Marketplace イメージのオファーの種類を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            たとえば、UbuntuServer または WindowsServer です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Publisher">
      <MemberSignature Language="C#" Value="public string Publisher { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Publisher" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ImageReference.Publisher" />
      <MemberSignature Language="VB.NET" Value="Public Property Publisher As String" />
      <MemberSignature Language="F#" Value="member this.Publisher : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ImageReference.Publisher" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="publisher")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure の仮想マシンの Marketplace イメージのパブリッシャーを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            たとえば、正規または MicrosoftWindowsServer です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public string Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ImageReference.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As String" />
      <MemberSignature Language="F#" Value="member this.Sku : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ImageReference.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure の仮想マシンの Marketplace イメージの SKU を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            たとえば、14.04.0-LTS または 2012 R2 Datacenter します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ImageReference.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ImageReference.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="version")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure の仮想マシンの Marketplace イメージのバージョンを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            イメージの最新バージョンを選択する 'latest' の値を指定することができます。 省略した場合、既定値は '最新' です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineImageId">
      <MemberSignature Language="C#" Value="public string VirtualMachineImageId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VirtualMachineImageId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ImageReference.VirtualMachineImageId" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachineImageId As String" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineImageId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ImageReference.VirtualMachineImageId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="virtualMachineImageId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバーチャル マシンのイメージを ARM リソース識別子を設定します。 このカスタム イメージを使用して、プールのノードが作成されますが計算されます。 これは、フォーム/subscriptions/{subscriptionId}/resourceGroups/{resourceGroup}/providers/Microsoft.Compute/images/{imageName の}
            </summary>
        <value>To be added.</value>
        <remarks>
            このプロパティは、その他の ImageReference プロパティで相互に排他的です。 バーチャル マシンのイメージは、同じリージョンと、Azure Batch アカウントとサブスクリプションにする必要があります。 バッチ サービスと通信するために Batch ノード エージェントに対するファイアウォール設定に関する情報は、https://docs.microsoft.com/en-us/azure/batch/batch-api-basics#virtual-network-vnet-and-firewall-configuration を参照してください。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>