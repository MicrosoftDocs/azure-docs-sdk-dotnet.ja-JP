<Type Name="TopicRegenerateKeyRequest" FullName="Microsoft.Azure.Management.EventGrid.Models.TopicRegenerateKeyRequest">
  <TypeSignature Language="C#" Value="public class TopicRegenerateKeyRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TopicRegenerateKeyRequest extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.EventGrid.Models.TopicRegenerateKeyRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class TopicRegenerateKeyRequest" />
  <TypeSignature Language="F#" Value="type TopicRegenerateKeyRequest = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0f62f-101">トピック再生成する共有アクセス キー キー要求</span><span class="sxs-lookup"><span data-stu-id="0f62f-101">Topic regenerate share access key key request</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TopicRegenerateKeyRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.Models.TopicRegenerateKeyRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0f62f-102">TopicRegenerateKeyRequest クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0f62f-102">Initializes a new instance of the TopicRegenerateKeyRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TopicRegenerateKeyRequest (string keyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string keyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.Models.TopicRegenerateKeyRequest.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (keyName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.EventGrid.Models.TopicRegenerateKeyRequest : string -&gt; Microsoft.Azure.Management.EventGrid.Models.TopicRegenerateKeyRequest" Usage="new Microsoft.Azure.Management.EventGrid.Models.TopicRegenerateKeyRequest keyName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyName"><span data-ttu-id="0f62f-103">Key1、key2 または再生成するキーの名前</span><span class="sxs-lookup"><span data-stu-id="0f62f-103">Key name to regenerate key1 or key2</span></span></param>
        <summary>
            <span data-ttu-id="0f62f-104">TopicRegenerateKeyRequest クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0f62f-104">Initializes a new instance of the TopicRegenerateKeyRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyName">
      <MemberSignature Language="C#" Value="public string KeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.TopicRegenerateKeyRequest.KeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyName As String" />
      <MemberSignature Language="F#" Value="member this.KeyName : string with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.TopicRegenerateKeyRequest.KeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0f62f-105">取得または設定するか、key1、key2 を再生成キーの名前</span><span class="sxs-lookup"><span data-stu-id="0f62f-105">Gets or sets key name to regenerate key1 or key2</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.Models.TopicRegenerateKeyRequest.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="topicRegenerateKeyRequest.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0f62f-106">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="0f62f-106">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0f62f-107">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0f62f-107">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>