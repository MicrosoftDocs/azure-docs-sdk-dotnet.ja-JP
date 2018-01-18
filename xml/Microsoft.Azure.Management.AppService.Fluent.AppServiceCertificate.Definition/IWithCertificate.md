<Type Name="IWithCertificate" FullName="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithCertificate">
  <TypeSignature Language="C#" Value="public interface IWithCertificate" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithCertificate" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithCertificate" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithCertificate" />
  <TypeSignature Language="F#" Value="type IWithCertificate = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="27ea2-101">PFX 証明書ファイルを設定するようにするアプリ サービスの証明書定義します。</span><span class="sxs-lookup"><span data-stu-id="27ea2-101">An app service certificate definition allowing PFX certificate file to be set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingCertificateOrder">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithCreate WithExistingCertificateOrder (Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder certificateOrder);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithCreate WithExistingCertificateOrder(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder certificateOrder) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithCertificate.WithExistingCertificateOrder(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingCertificateOrder (certificateOrder As IAppServiceCertificateOrder) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingCertificateOrder : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder -&gt; Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithCreate" Usage="iWithCertificate.WithExistingCertificateOrder certificateOrder" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="certificateOrder" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder" />
      </Parameters>
      <Docs>
        <param name="certificateOrder"><span data-ttu-id="27ea2-102">アプリのサービス証明書の順序。</span><span class="sxs-lookup"><span data-stu-id="27ea2-102">The app service certificate order.</span></span></param>
        <summary>
            <span data-ttu-id="27ea2-103">アプリのサービス証明書を指定します。</span><span class="sxs-lookup"><span data-stu-id="27ea2-103">Specifies the app service certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="27ea2-104">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="27ea2-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPfxByteArray">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithPfxFilePassword WithPfxByteArray (params byte[] pfxByteArray);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithPfxFilePassword WithPfxByteArray(unsigned int8[] pfxByteArray) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithCertificate.WithPfxByteArray(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPfxByteArray (ParamArray pfxByteArray As Byte()) As IWithPfxFilePassword" />
      <MemberSignature Language="F#" Value="abstract member WithPfxByteArray : byte[] -&gt; Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithPfxFilePassword" Usage="iWithCertificate.WithPfxByteArray pfxByteArray" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithPfxFilePassword</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="pfxByteArray" Type="System.Byte[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="pfxByteArray"><span data-ttu-id="27ea2-105">PFX のバイト配列。</span><span class="sxs-lookup"><span data-stu-id="27ea2-105">The PFX byte array.</span></span></param>
        <summary>
            <span data-ttu-id="27ea2-106">アップロードする PFX バイト配列を指定します。</span><span class="sxs-lookup"><span data-stu-id="27ea2-106">Specifies the PFX byte array to upload.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="27ea2-107">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="27ea2-107">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPfxFile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithPfxFilePassword WithPfxFile (string file);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithPfxFilePassword WithPfxFile(string file) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithCertificate.WithPfxFile(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPfxFile (file As String) As IWithPfxFilePassword" />
      <MemberSignature Language="F#" Value="abstract member WithPfxFile : string -&gt; Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithPfxFilePassword" Usage="iWithCertificate.WithPfxFile file" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithPfxFilePassword</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="file" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="file"><span data-ttu-id="27ea2-108">PFX 証明書ファイル。</span><span class="sxs-lookup"><span data-stu-id="27ea2-108">The PFX certificate file.</span></span></param>
        <summary>
            <span data-ttu-id="27ea2-109">アップロードする PFX 証明書ファイルを指定します。</span><span class="sxs-lookup"><span data-stu-id="27ea2-109">Specifies the PFX certificate file to upload.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="27ea2-110">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="27ea2-110">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPfxFileFromUrl">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithPfxFilePassword WithPfxFileFromUrl (string url);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithPfxFilePassword WithPfxFileFromUrl(string url) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithCertificate.WithPfxFileFromUrl(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPfxFileFromUrl (url As String) As IWithPfxFilePassword" />
      <MemberSignature Language="F#" Value="abstract member WithPfxFileFromUrl : string -&gt; Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithPfxFilePassword" Usage="iWithCertificate.WithPfxFileFromUrl url" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithPfxFilePassword</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="url" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="url"><span data-ttu-id="27ea2-111">PFX ファイルを指す URL です。</span><span class="sxs-lookup"><span data-stu-id="27ea2-111">The URL pointing to the PFX file.</span></span></param>
        <summary>
            <span data-ttu-id="27ea2-112">URL から、PFX ファイルを指定します。</span><span class="sxs-lookup"><span data-stu-id="27ea2-112">Specifies the PFX file from a URL.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="27ea2-113">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="27ea2-113">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>