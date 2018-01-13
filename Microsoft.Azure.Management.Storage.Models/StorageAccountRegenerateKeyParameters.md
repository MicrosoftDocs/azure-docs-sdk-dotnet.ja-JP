<Type Name="StorageAccountRegenerateKeyParameters" FullName="Microsoft.Azure.Management.Storage.Models.StorageAccountRegenerateKeyParameters">
  <TypeSignature Language="C#" Value="public class StorageAccountRegenerateKeyParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StorageAccountRegenerateKeyParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Models.StorageAccountRegenerateKeyParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class StorageAccountRegenerateKeyParameters" />
  <TypeSignature Language="F#" Value="type StorageAccountRegenerateKeyParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
    <AssemblyVersion>7.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ストレージ アカウント キーを再生成するために使用するパラメーターです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountRegenerateKeyParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.StorageAccountRegenerateKeyParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            StorageAccountRegenerateKeyParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountRegenerateKeyParameters (string keyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string keyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.StorageAccountRegenerateKeyParameters.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (keyName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Models.StorageAccountRegenerateKeyParameters : string -&gt; Microsoft.Azure.Management.Storage.Models.StorageAccountRegenerateKeyParameters" Usage="new Microsoft.Azure.Management.Storage.Models.StorageAccountRegenerateKeyParameters keyName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyName">再生成された、可能な値を許可する記憶域のキーの名前は、key1、key2 です。</param>
        <summary>
            StorageAccountRegenerateKeyParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyName">
      <MemberSignature Language="C#" Value="public string KeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountRegenerateKeyParameters.KeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyName As String" />
      <MemberSignature Language="F#" Value="member this.KeyName : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountRegenerateKeyParameters.KeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
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
            記憶域の名前を取得または設定は、キーの再生成する場合、可能な値は key1、key2 です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.StorageAccountRegenerateKeyParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="storageAccountRegenerateKeyParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>