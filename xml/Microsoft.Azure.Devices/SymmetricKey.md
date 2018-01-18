<Type Name="SymmetricKey" FullName="Microsoft.Azure.Devices.SymmetricKey">
  <TypeSignature Language="C#" Value="public sealed class SymmetricKey" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SymmetricKey extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.SymmetricKey" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SymmetricKey" />
  <TypeSignature Language="F#" Value="type SymmetricKey = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="04ef1-101">デバイスの対称キーをプライマリおよびセカンダリ。</span><span class="sxs-lookup"><span data-stu-id="04ef1-101">primary and secondary symmetric keys of a device.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SymmetricKey ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.SymmetricKey.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsEmpty">
      <MemberSignature Language="C#" Value="public bool IsEmpty ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool IsEmpty() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.SymmetricKey.IsEmpty" />
      <MemberSignature Language="VB.NET" Value="Public Function IsEmpty () As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsEmpty : unit -&gt; bool" Usage="symmetricKey.IsEmpty " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="04ef1-102">かどうかは、フィールドが設定を確認します。</span><span class="sxs-lookup"><span data-stu-id="04ef1-102">Checks if the fields are populated</span></span>
            </summary>
        <returns><span data-ttu-id="04ef1-103">bool</span><span class="sxs-lookup"><span data-stu-id="04ef1-103">bool</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsValid">
      <MemberSignature Language="C#" Value="public bool IsValid (bool throwArgumentException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool IsValid(bool throwArgumentException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.SymmetricKey.IsValid(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function IsValid (throwArgumentException As Boolean) As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsValid : bool -&gt; bool" Usage="symmetricKey.IsValid throwArgumentException" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="throwArgumentException" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="throwArgumentException"></param>
        <summary>
            <span data-ttu-id="04ef1-104">内容が有効なかどうかを確認します。</span><span class="sxs-lookup"><span data-stu-id="04ef1-104">Checks if the contents are valid</span></span>
            </summary>
        <returns><span data-ttu-id="04ef1-105">bool</span><span class="sxs-lookup"><span data-stu-id="04ef1-105">bool</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryKey">
      <MemberSignature Language="C#" Value="public string PrimaryKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimaryKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.SymmetricKey.PrimaryKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimaryKey As String" />
      <MemberSignature Language="F#" Value="member this.PrimaryKey : string with get, set" Usage="Microsoft.Azure.Devices.SymmetricKey.PrimaryKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="04ef1-106">取得または設定の主キー</span><span class="sxs-lookup"><span data-stu-id="04ef1-106">Gets or sets the PrimaryKey</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryKey">
      <MemberSignature Language="C#" Value="public string SecondaryKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecondaryKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.SymmetricKey.SecondaryKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondaryKey As String" />
      <MemberSignature Language="F#" Value="member this.SecondaryKey : string with get, set" Usage="Microsoft.Azure.Devices.SymmetricKey.SecondaryKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="04ef1-107">取得または設定、SecondaryKey</span><span class="sxs-lookup"><span data-stu-id="04ef1-107">Gets or sets the SecondaryKey</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>