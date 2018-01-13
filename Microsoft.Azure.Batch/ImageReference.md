<Type Name="ImageReference" FullName="Microsoft.Azure.Batch.ImageReference">
  <TypeSignature Language="C#" Value="public class ImageReference" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ImageReference extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.ImageReference" />
  <TypeSignature Language="VB.NET" Value="Public Class ImageReference" />
  <TypeSignature Language="F#" Value="type ImageReference = class&#xA;    interface ITransportObjectProvider&lt;ImageReference&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            Azure の仮想マシンのイメージです。 Azure Batch によって検証 Azure Marketplace イメージのすべての参照の一覧を取得するには、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.ListNodeAgentSkus(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />と<see cref="P:Microsoft.Azure.Batch.NodeAgentSku.VerifiedImageReferences" />です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageReference (string virtualMachineImageId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string virtualMachineImageId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ImageReference.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (virtualMachineImageId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.ImageReference : string -&gt; Microsoft.Azure.Batch.ImageReference" Usage="new Microsoft.Azure.Batch.ImageReference virtualMachineImageId" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="virtualMachineImageId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="virtualMachineImageId">
            バーチャル マシンのイメージを ARM リソース識別子です。 このカスタム イメージを使用して、プールのノードが作成されますが計算されます。 これは、フォーム/subscriptions/{subscriptionId}/resourceGroups/{resourceGroup}/providers/Microsoft.Compute/images/{imageName の}
            </param>
        <summary>
            <see cref="T:Microsoft.Azure.Batch.ImageReference" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageReference (string offer, string publisher, string sku, string version = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string offer, string publisher, string sku, string version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ImageReference.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (offer As String, publisher As String, sku As String, Optional version As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.ImageReference : string * string * string * string -&gt; Microsoft.Azure.Batch.ImageReference" Usage="new Microsoft.Azure.Batch.ImageReference (offer, publisher, sku, version)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="offer" Type="System.String" />
        <Parameter Name="publisher" Type="System.String" />
        <Parameter Name="sku" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="offer">Azure の仮想マシンの Marketplace イメージのオファーの種類。</param>
        <param name="publisher">Azure の仮想マシンの Marketplace イメージのパブリッシャーです。</param>
        <param name="sku">Azure の仮想マシンの Marketplace イメージの SKU。</param>
        <param name="version">Azure の仮想マシンの Marketplace イメージのバージョン。</param>
        <summary>
            <see cref="T:Microsoft.Azure.Batch.ImageReference" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Offer">
      <MemberSignature Language="C#" Value="public string Offer { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Offer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ImageReference.Offer" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Offer As String" />
      <MemberSignature Language="F#" Value="member this.Offer : string" Usage="Microsoft.Azure.Batch.ImageReference.Offer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure の仮想マシンの Marketplace イメージのオファーの種類を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
            たとえば、UbuntuServer または WindowsServer です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Publisher">
      <MemberSignature Language="C#" Value="public string Publisher { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Publisher" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ImageReference.Publisher" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Publisher As String" />
      <MemberSignature Language="F#" Value="member this.Publisher : string" Usage="Microsoft.Azure.Batch.ImageReference.Publisher" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure の仮想マシンの Marketplace イメージのパブリッシャーを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
            たとえば、正規または MicrosoftWindowsServer です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public string Sku { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ImageReference.Sku" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Sku As String" />
      <MemberSignature Language="F#" Value="member this.Sku : string" Usage="Microsoft.Azure.Batch.ImageReference.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure の仮想マシンの Marketplace イメージの SKU を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
            たとえば、14.04.0-LTS または 2012 R2 Datacenter します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ImageReference.Version" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string" Usage="Microsoft.Azure.Batch.ImageReference.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure の仮想マシンの Marketplace イメージのバージョンを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
            このプロパティが指定されていない場合の既定値は 'latest' は、イメージの最新バージョンです。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineImageId">
      <MemberSignature Language="C#" Value="public string VirtualMachineImageId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VirtualMachineImageId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ImageReference.VirtualMachineImageId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineImageId As String" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineImageId : string" Usage="Microsoft.Azure.Batch.ImageReference.VirtualMachineImageId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            バーチャル マシンのイメージを ARM リソース識別子を取得します。 このカスタム イメージを使用して、プールのノードが作成されますが計算されます。 これは、フォーム/subscriptions/{subscriptionId}/resourceGroups/{resourceGroup}/providers/Microsoft.Compute/images/{imageName の}
            </summary>
        <value>To be added.</value>
        <remarks>
            このプロパティは、その他の ImageReference プロパティで相互に排他的です。 バーチャル マシンのイメージは、同じリージョンと、Azure Batch アカウントとサブスクリプションにする必要があります。 バッチ サービスと通信するために Batch ノード エージェントに対するファイアウォール設定に関する情報は、https://docs.microsoft.com/en-us/azure/batch/batch-api-basics#virtual-network-vnet-and-firewall-configuration を参照してください。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>