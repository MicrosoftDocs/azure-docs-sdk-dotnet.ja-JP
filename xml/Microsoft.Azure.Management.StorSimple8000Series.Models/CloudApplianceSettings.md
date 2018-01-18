<Type Name="CloudApplianceSettings" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceSettings">
  <TypeSignature Language="C#" Value="public class CloudApplianceSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudApplianceSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudApplianceSettings" />
  <TypeSignature Language="F#" Value="type CloudApplianceSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="687b3-101">クラウド アプライアンスの設定。</span><span class="sxs-lookup"><span data-stu-id="687b3-101">The cloud appliance settings.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudApplianceSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="687b3-102">CloudApplianceSettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="687b3-102">Initializes a new instance of the CloudApplianceSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudApplianceSettings (Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret serviceDataEncryptionKey = null, Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret channelIntegrityKey = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret serviceDataEncryptionKey, class Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret channelIntegrityKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceSettings.#ctor(Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret,Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional serviceDataEncryptionKey As AsymmetricEncryptedSecret = null, Optional channelIntegrityKey As AsymmetricEncryptedSecret = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceSettings : Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret * Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceSettings" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceSettings (serviceDataEncryptionKey, channelIntegrityKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceDataEncryptionKey" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret" />
        <Parameter Name="channelIntegrityKey" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret" />
      </Parameters>
      <Docs>
        <param name="serviceDataEncryptionKey"><span data-ttu-id="687b3-103">サービス データ暗号化キー (DAK で暗号化された)。</span><span class="sxs-lookup"><span data-stu-id="687b3-103">The service data encryption key (encrypted with DAK).</span></span></param>
        <param name="channelIntegrityKey"><span data-ttu-id="687b3-104">(DAK で暗号化された) チャネル整合性キー。</span><span class="sxs-lookup"><span data-stu-id="687b3-104">The channel integrity key (encrypted with DAK).</span></span></param>
        <summary>
            <span data-ttu-id="687b3-105">CloudApplianceSettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="687b3-105">Initializes a new instance of the CloudApplianceSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChannelIntegrityKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret ChannelIntegrityKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret ChannelIntegrityKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceSettings.ChannelIntegrityKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ChannelIntegrityKey As AsymmetricEncryptedSecret" />
      <MemberSignature Language="F#" Value="member this.ChannelIntegrityKey : Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceSettings.ChannelIntegrityKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="channelIntegrityKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="687b3-106">取得または (DAK で暗号化された) チャネル整合性キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="687b3-106">Gets or sets the channel integrity key (encrypted with DAK).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceDataEncryptionKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret ServiceDataEncryptionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret ServiceDataEncryptionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceSettings.ServiceDataEncryptionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceDataEncryptionKey As AsymmetricEncryptedSecret" />
      <MemberSignature Language="F#" Value="member this.ServiceDataEncryptionKey : Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceSettings.ServiceDataEncryptionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="serviceDataEncryptionKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="687b3-107">取得または (DAK で暗号化された)、サービス データ暗号化キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="687b3-107">Gets or sets the service data encryption key (encrypted with DAK).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="cloudApplianceSettings.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="687b3-108">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="687b3-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="687b3-109">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="687b3-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>