<Type Name="RedisRegenerateKeyParameters" FullName="Microsoft.Azure.Management.Redis.Models.RedisRegenerateKeyParameters">
  <TypeSignature Language="C#" Value="public class RedisRegenerateKeyParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RedisRegenerateKeyParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Models.RedisRegenerateKeyParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class RedisRegenerateKeyParameters" />
  <TypeSignature Language="F#" Value="type RedisRegenerateKeyParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f8ef4-101">リセットする Redis アクセス キーを指定します。</span><span class="sxs-lookup"><span data-stu-id="f8ef4-101">Specifies which Redis access keys to reset.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RedisRegenerateKeyParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.RedisRegenerateKeyParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f8ef4-102">RedisRegenerateKeyParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f8ef4-102">Initializes a new instance of the RedisRegenerateKeyParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RedisRegenerateKeyParameters (Microsoft.Azure.Management.Redis.Models.RedisKeyType keyType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Redis.Models.RedisKeyType keyType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.RedisRegenerateKeyParameters.#ctor(Microsoft.Azure.Management.Redis.Models.RedisKeyType)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (keyType As RedisKeyType)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Redis.Models.RedisRegenerateKeyParameters : Microsoft.Azure.Management.Redis.Models.RedisKeyType -&gt; Microsoft.Azure.Management.Redis.Models.RedisRegenerateKeyParameters" Usage="new Microsoft.Azure.Management.Redis.Models.RedisRegenerateKeyParameters keyType" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keyType" Type="Microsoft.Azure.Management.Redis.Models.RedisKeyType" />
      </Parameters>
      <Docs>
        <param name="keyType"><span data-ttu-id="f8ef4-103">Redis アクセス キーを再生成します。</span><span class="sxs-lookup"><span data-stu-id="f8ef4-103">The Redis access key to regenerate.</span></span> <span data-ttu-id="f8ef4-104">使用可能な値が含まれます 'Primary'、'セカンダリ'。</span><span class="sxs-lookup"><span data-stu-id="f8ef4-104">Possible values include: 'Primary', 'Secondary'</span></span></param>
        <summary>
            <span data-ttu-id="f8ef4-105">RedisRegenerateKeyParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f8ef4-105">Initializes a new instance of the RedisRegenerateKeyParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Models.RedisKeyType KeyType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Redis.Models.RedisKeyType KeyType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisRegenerateKeyParameters.KeyType" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyType As RedisKeyType" />
      <MemberSignature Language="F#" Value="member this.KeyType : Microsoft.Azure.Management.Redis.Models.RedisKeyType with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisRegenerateKeyParameters.KeyType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Models.RedisKeyType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8ef4-106">取得または再生成する Redis アクセス キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="f8ef4-106">Gets or sets the Redis access key to regenerate.</span></span> <span data-ttu-id="f8ef4-107">使用可能な値が含まれます 'Primary'、'セカンダリ'。</span><span class="sxs-lookup"><span data-stu-id="f8ef4-107">Possible values include: 'Primary', 'Secondary'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.RedisRegenerateKeyParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="redisRegenerateKeyParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f8ef4-108">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="f8ef4-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f8ef4-109">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f8ef4-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>