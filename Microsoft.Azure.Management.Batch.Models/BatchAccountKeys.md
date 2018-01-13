<Type Name="BatchAccountKeys" FullName="Microsoft.Azure.Management.Batch.Models.BatchAccountKeys">
  <TypeSignature Language="C#" Value="public class BatchAccountKeys" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BatchAccountKeys extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.BatchAccountKeys" />
  <TypeSignature Language="VB.NET" Value="Public Class BatchAccountKeys" />
  <TypeSignature Language="F#" Value="type BatchAccountKeys = class" />
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
            <span data-ttu-id="ea9f4-101">Azure Batch アカウント キーのセット。</span><span class="sxs-lookup"><span data-stu-id="ea9f4-101">A set of Azure Batch account keys.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchAccountKeys ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.BatchAccountKeys.#ctor" />
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
            <span data-ttu-id="ea9f4-102">BatchAccountKeys クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ea9f4-102">Initializes a new instance of the BatchAccountKeys class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchAccountKeys (string accountName = null, string primary = null, string secondary = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string accountName, string primary, string secondary) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.BatchAccountKeys.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional accountName As String = null, Optional primary As String = null, Optional secondary As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.BatchAccountKeys : string * string * string -&gt; Microsoft.Azure.Management.Batch.Models.BatchAccountKeys" Usage="new Microsoft.Azure.Management.Batch.Models.BatchAccountKeys (accountName, primary, secondary)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="primary" Type="System.String" />
        <Parameter Name="secondary" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="accountName"><span data-ttu-id="ea9f4-103">Batch アカウント名。</span><span class="sxs-lookup"><span data-stu-id="ea9f4-103">The Batch account name.</span></span></param>
        <param name="primary"><span data-ttu-id="ea9f4-104">アカウントに関連付けられている主キー。</span><span class="sxs-lookup"><span data-stu-id="ea9f4-104">The primary key associated with the account.</span></span></param>
        <param name="secondary"><span data-ttu-id="ea9f4-105">アカウントに関連付けられているセカンダリ キー。</span><span class="sxs-lookup"><span data-stu-id="ea9f4-105">The secondary key associated with the account.</span></span></param>
        <summary>
            <span data-ttu-id="ea9f4-106">BatchAccountKeys クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ea9f4-106">Initializes a new instance of the BatchAccountKeys class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountName">
      <MemberSignature Language="C#" Value="public string AccountName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccountName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.BatchAccountKeys.AccountName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccountName As String" />
      <MemberSignature Language="F#" Value="member this.AccountName : string" Usage="Microsoft.Azure.Management.Batch.Models.BatchAccountKeys.AccountName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="accountName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea9f4-107">Batch アカウント名を取得します。</span><span class="sxs-lookup"><span data-stu-id="ea9f4-107">Gets the Batch account name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Primary">
      <MemberSignature Language="C#" Value="public string Primary { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Primary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.BatchAccountKeys.Primary" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Primary As String" />
      <MemberSignature Language="F#" Value="member this.Primary : string" Usage="Microsoft.Azure.Management.Batch.Models.BatchAccountKeys.Primary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="primary")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea9f4-108">アカウントに関連付けられている主キーを取得します。</span><span class="sxs-lookup"><span data-stu-id="ea9f4-108">Gets the primary key associated with the account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Secondary">
      <MemberSignature Language="C#" Value="public string Secondary { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Secondary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.BatchAccountKeys.Secondary" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Secondary As String" />
      <MemberSignature Language="F#" Value="member this.Secondary : string" Usage="Microsoft.Azure.Management.Batch.Models.BatchAccountKeys.Secondary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secondary")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea9f4-109">アカウントに関連付けられたセカンダリ キーを取得します。</span><span class="sxs-lookup"><span data-stu-id="ea9f4-109">Gets the secondary key associated with the account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>