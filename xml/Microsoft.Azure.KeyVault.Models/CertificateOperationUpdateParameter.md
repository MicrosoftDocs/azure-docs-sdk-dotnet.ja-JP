<Type Name="CertificateOperationUpdateParameter" FullName="Microsoft.Azure.KeyVault.Models.CertificateOperationUpdateParameter">
  <TypeSignature Language="C#" Value="public class CertificateOperationUpdateParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateOperationUpdateParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.CertificateOperationUpdateParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateOperationUpdateParameter" />
  <TypeSignature Language="F#" Value="type CertificateOperationUpdateParameter = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="87c62-101">証明書操作パラメーターを変更しています。</span><span class="sxs-lookup"><span data-stu-id="87c62-101">The certificate operation update parameters.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateOperationUpdateParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.CertificateOperationUpdateParameter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="87c62-102">CertificateOperationUpdateParameter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="87c62-102">Initializes a new instance of the CertificateOperationUpdateParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateOperationUpdateParameter (bool cancellationRequested);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(bool cancellationRequested) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.CertificateOperationUpdateParameter.#ctor(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (cancellationRequested As Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.CertificateOperationUpdateParameter : bool -&gt; Microsoft.Azure.KeyVault.Models.CertificateOperationUpdateParameter" Usage="new Microsoft.Azure.KeyVault.Models.CertificateOperationUpdateParameter cancellationRequested" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="cancellationRequested" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="cancellationRequested"><span data-ttu-id="87c62-103">証明書の操作のキャンセルが要求されたかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="87c62-103">Indicates if cancellation was requested on the certificate operation.</span></span></param>
        <summary>
            <span data-ttu-id="87c62-104">CertificateOperationUpdateParameter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="87c62-104">Initializes a new instance of the CertificateOperationUpdateParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancellationRequested">
      <MemberSignature Language="C#" Value="public bool CancellationRequested { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool CancellationRequested" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateOperationUpdateParameter.CancellationRequested" />
      <MemberSignature Language="VB.NET" Value="Public Property CancellationRequested As Boolean" />
      <MemberSignature Language="F#" Value="member this.CancellationRequested : bool with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateOperationUpdateParameter.CancellationRequested" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="cancellation_requested")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="87c62-105">取得または設定は、証明書の操作のキャンセルが要求されたかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="87c62-105">Gets or sets indicates if cancellation was requested on the certificate operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.CertificateOperationUpdateParameter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="certificateOperationUpdateParameter.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="87c62-106">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="87c62-106">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="87c62-107">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="87c62-107">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>