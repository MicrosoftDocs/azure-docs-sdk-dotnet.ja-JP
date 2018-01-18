<Type Name="BatchAccountRegenerateKeyParameters" FullName="Microsoft.Azure.Management.Batch.Models.BatchAccountRegenerateKeyParameters">
  <TypeSignature Language="C#" Value="public class BatchAccountRegenerateKeyParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BatchAccountRegenerateKeyParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.BatchAccountRegenerateKeyParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class BatchAccountRegenerateKeyParameters" />
  <TypeSignature Language="F#" Value="type BatchAccountRegenerateKeyParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="76c99-101">RegenerateKey 操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="76c99-101">Parameters supplied to the RegenerateKey operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchAccountRegenerateKeyParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.BatchAccountRegenerateKeyParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="76c99-102">BatchAccountRegenerateKeyParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="76c99-102">Initializes a new instance of the BatchAccountRegenerateKeyParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchAccountRegenerateKeyParameters (Microsoft.Azure.Management.Batch.Models.AccountKeyType keyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Batch.Models.AccountKeyType keyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.BatchAccountRegenerateKeyParameters.#ctor(Microsoft.Azure.Management.Batch.Models.AccountKeyType)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (keyName As AccountKeyType)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.BatchAccountRegenerateKeyParameters : Microsoft.Azure.Management.Batch.Models.AccountKeyType -&gt; Microsoft.Azure.Management.Batch.Models.BatchAccountRegenerateKeyParameters" Usage="new Microsoft.Azure.Management.Batch.Models.BatchAccountRegenerateKeyParameters keyName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keyName" Type="Microsoft.Azure.Management.Batch.Models.AccountKeyType" />
      </Parameters>
      <Docs>
        <param name="keyName"><span data-ttu-id="76c99-103">アカウント キーを再生成の型。</span><span class="sxs-lookup"><span data-stu-id="76c99-103">The type of account key to regenerate.</span></span>
            <span data-ttu-id="76c99-104">使用可能な値が含まれます 'Primary'、'セカンダリ'。</span><span class="sxs-lookup"><span data-stu-id="76c99-104">Possible values include: 'Primary', 'Secondary'</span></span></param>
        <summary>
            <span data-ttu-id="76c99-105">BatchAccountRegenerateKeyParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="76c99-105">Initializes a new instance of the BatchAccountRegenerateKeyParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyName">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.AccountKeyType KeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Batch.Models.AccountKeyType KeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.BatchAccountRegenerateKeyParameters.KeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyName As AccountKeyType" />
      <MemberSignature Language="F#" Value="member this.KeyName : Microsoft.Azure.Management.Batch.Models.AccountKeyType with get, set" Usage="Microsoft.Azure.Management.Batch.Models.BatchAccountRegenerateKeyParameters.KeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.AccountKeyType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="76c99-106">取得または設定を再生成するアカウント キーの型。</span><span class="sxs-lookup"><span data-stu-id="76c99-106">Gets or sets the type of account key to regenerate.</span></span> <span data-ttu-id="76c99-107">使用可能な値が含まれます 'Primary'、'セカンダリ'。</span><span class="sxs-lookup"><span data-stu-id="76c99-107">Possible values include: 'Primary', 'Secondary'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.BatchAccountRegenerateKeyParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="batchAccountRegenerateKeyParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="76c99-108">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="76c99-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="76c99-109">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76c99-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>