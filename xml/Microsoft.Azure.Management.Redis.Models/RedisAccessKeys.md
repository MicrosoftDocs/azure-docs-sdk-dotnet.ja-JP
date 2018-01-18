<Type Name="RedisAccessKeys" FullName="Microsoft.Azure.Management.Redis.Models.RedisAccessKeys">
  <TypeSignature Language="C#" Value="public class RedisAccessKeys" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RedisAccessKeys extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Models.RedisAccessKeys" />
  <TypeSignature Language="VB.NET" Value="Public Class RedisAccessKeys" />
  <TypeSignature Language="F#" Value="type RedisAccessKeys = class" />
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
            <span data-ttu-id="b1c47-101">Cache のアクセス キーを redis します。</span><span class="sxs-lookup"><span data-stu-id="b1c47-101">Redis cache access keys.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RedisAccessKeys ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.RedisAccessKeys.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b1c47-102">RedisAccessKeys クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b1c47-102">Initializes a new instance of the RedisAccessKeys class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RedisAccessKeys (string primaryKey = null, string secondaryKey = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string primaryKey, string secondaryKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.RedisAccessKeys.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional primaryKey As String = null, Optional secondaryKey As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Redis.Models.RedisAccessKeys : string * string -&gt; Microsoft.Azure.Management.Redis.Models.RedisAccessKeys" Usage="new Microsoft.Azure.Management.Redis.Models.RedisAccessKeys (primaryKey, secondaryKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="primaryKey" Type="System.String" />
        <Parameter Name="secondaryKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="primaryKey"><span data-ttu-id="b1c47-103">クライアントは、Redis cache での認証に使用できる現在のプライマリ キー。</span><span class="sxs-lookup"><span data-stu-id="b1c47-103">The current primary key that clients can use to authenticate with Redis cache.</span></span></param>
        <param name="secondaryKey"><span data-ttu-id="b1c47-104">クライアントは、Redis cache での認証に使用できる現在のセカンダリ キー。</span><span class="sxs-lookup"><span data-stu-id="b1c47-104">The current secondary key that clients can use to authenticate with Redis cache.</span></span></param>
        <summary>
            <span data-ttu-id="b1c47-105">RedisAccessKeys クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b1c47-105">Initializes a new instance of the RedisAccessKeys class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryKey">
      <MemberSignature Language="C#" Value="public string PrimaryKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimaryKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisAccessKeys.PrimaryKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrimaryKey As String" />
      <MemberSignature Language="F#" Value="member this.PrimaryKey : string" Usage="Microsoft.Azure.Management.Redis.Models.RedisAccessKeys.PrimaryKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="primaryKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b1c47-106">クライアントは、Redis cache での認証に使用できる現在のプライマリ キーを取得します。</span><span class="sxs-lookup"><span data-stu-id="b1c47-106">Gets the current primary key that clients can use to authenticate with Redis cache.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryKey">
      <MemberSignature Language="C#" Value="public string SecondaryKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecondaryKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisAccessKeys.SecondaryKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SecondaryKey As String" />
      <MemberSignature Language="F#" Value="member this.SecondaryKey : string" Usage="Microsoft.Azure.Management.Redis.Models.RedisAccessKeys.SecondaryKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secondaryKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b1c47-107">クライアントは、Redis cache での認証に使用できる現在のセカンダリ キーを取得します。</span><span class="sxs-lookup"><span data-stu-id="b1c47-107">Gets the current secondary key that clients can use to authenticate with Redis cache.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>