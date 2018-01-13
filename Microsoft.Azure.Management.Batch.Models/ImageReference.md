<Type Name="ImageReference" FullName="Microsoft.Azure.Management.Batch.Models.ImageReference">
  <TypeSignature Language="C#" Value="public class ImageReference" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ImageReference extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.ImageReference" />
  <TypeSignature Language="VB.NET" Value="Public Class ImageReference" />
  <TypeSignature Language="F#" Value="type ImageReference = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Azure の仮想マシンの Marketplace イメージまたはカスタムの仮想マシンの Azure イメージ リソースへの参照。 Azure Batch によって検証すべて Imagereference の一覧を取得するには、'リストには、ノード エージェント Sku がサポートされている' 操作を参照してください。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.ImageReference.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public ImageReference (string publisher = null, string offer = null, string sku = null, string version = null, string id = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string publisher, string offer, string sku, string version, string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.ImageReference.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional publisher As String = null, Optional offer As String = null, Optional sku As String = null, Optional version As String = null, Optional id As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.ImageReference : string * string * string * string * string -&gt; Microsoft.Azure.Management.Batch.Models.ImageReference" Usage="new Microsoft.Azure.Management.Batch.Models.ImageReference (publisher, offer, sku, version, id)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="publisher" Type="System.String" />
        <Parameter Name="offer" Type="System.String" />
        <Parameter Name="sku" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="publisher">Azure の仮想マシンの Marketplace イメージのパブリッシャーです。</param>
        <param name="offer">Azure の仮想マシンの Marketplace イメージのオファーの種類。</param>
        <param name="sku">Azure の仮想マシンの Marketplace イメージの SKU。</param>
        <param name="version">Azure の仮想マシンの Marketplace イメージのバージョン。</param>
        <param name="id">バーチャル マシンのイメージを ARM リソース識別子です。 このカスタム イメージを使用して、プールのノードが作成されますが計算されます。 これは、フォーム/subscriptions/{subscriptionId}/resourceGroups/{resourceGroup}/providers/Microsoft.Compute/images/{imageName の}</param>
        <summary>
            ImageReference クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ImageReference.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.ImageReference.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
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
            このプロパティは、その他のプロパティで相互に排他的です。 バーチャル マシンのイメージは、同じリージョンと、Azure Batch アカウントとサブスクリプションにする必要があります。 バッチ サービスと通信する Batch ノード エージェントに対するファイアウォール設定に関する情報は、https://docs.microsoft.com/en-us/azure/batch/batch-api-basics#virtual-network-vnet-and-firewall-configuration を参照してください。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Offer">
      <MemberSignature Language="C#" Value="public string Offer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Offer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ImageReference.Offer" />
      <MemberSignature Language="VB.NET" Value="Public Property Offer As String" />
      <MemberSignature Language="F#" Value="member this.Offer : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.ImageReference.Offer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ImageReference.Publisher" />
      <MemberSignature Language="VB.NET" Value="Public Property Publisher As String" />
      <MemberSignature Language="F#" Value="member this.Publisher : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.ImageReference.Publisher" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ImageReference.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As String" />
      <MemberSignature Language="F#" Value="member this.Sku : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.ImageReference.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ImageReference.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.ImageReference.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
  </Members>
</Type>