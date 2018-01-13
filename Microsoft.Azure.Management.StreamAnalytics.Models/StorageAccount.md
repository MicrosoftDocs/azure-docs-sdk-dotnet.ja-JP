<Type Name="StorageAccount" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount">
  <TypeSignature Language="C#" Value="public class StorageAccount" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StorageAccount extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount" />
  <TypeSignature Language="VB.NET" Value="Public Class StorageAccount" />
  <TypeSignature Language="F#" Value="type StorageAccount = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Azure ストレージ アカウントに関連付けられているプロパティ
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccount ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            StorageAccount クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccount (string accountName = null, string accountKey = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string accountName, string accountKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional accountName As String = null, Optional accountKey As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount : string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount (accountName, accountKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="accountKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="accountName">Azure ストレージ アカウントの名前。
            PUT (CreateOrReplace) 要求に必要です。</param>
        <param name="accountKey">Azure ストレージ アカウントのアカウント キー。 PUT (CreateOrReplace) 要求に必要です。</param>
        <summary>
            StorageAccount クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountKey">
      <MemberSignature Language="C#" Value="public string AccountKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccountKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount.AccountKey" />
      <MemberSignature Language="VB.NET" Value="Public Property AccountKey As String" />
      <MemberSignature Language="F#" Value="member this.AccountKey : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount.AccountKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="accountKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure ストレージ アカウントのアカウント キーを設定します。
            PUT (CreateOrReplace) 要求に必要です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountName">
      <MemberSignature Language="C#" Value="public string AccountName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccountName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount.AccountName" />
      <MemberSignature Language="VB.NET" Value="Public Property AccountName As String" />
      <MemberSignature Language="F#" Value="member this.AccountName : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount.AccountName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            取得または Azure ストレージ アカウントの名前を設定します。 PUT (CreateOrReplace) 要求に必要です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>