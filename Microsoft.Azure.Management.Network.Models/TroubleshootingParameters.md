<Type Name="TroubleshootingParameters" FullName="Microsoft.Azure.Management.Network.Models.TroubleshootingParameters">
  <TypeSignature Language="C#" Value="public class TroubleshootingParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TroubleshootingParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.TroubleshootingParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class TroubleshootingParameters" />
  <TypeSignature Language="F#" Value="type TroubleshootingParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="4686a-101">トラブルシューティングのリソースを定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="4686a-101">Parameters that define the resource to troubleshoot.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TroubleshootingParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.TroubleshootingParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4686a-102">TroubleshootingParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4686a-102">Initializes a new instance of the TroubleshootingParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TroubleshootingParameters (string targetResourceId, string storageId, string storagePath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string targetResourceId, string storageId, string storagePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.TroubleshootingParameters.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (targetResourceId As String, storageId As String, storagePath As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.TroubleshootingParameters : string * string * string -&gt; Microsoft.Azure.Management.Network.Models.TroubleshootingParameters" Usage="new Microsoft.Azure.Management.Network.Models.TroubleshootingParameters (targetResourceId, storageId, storagePath)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="targetResourceId" Type="System.String" />
        <Parameter Name="storageId" Type="System.String" />
        <Parameter Name="storagePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="targetResourceId"><span data-ttu-id="4686a-103">トラブルシューティングを行うにターゲット リソースです。</span><span class="sxs-lookup"><span data-stu-id="4686a-103">The target resource to troubleshoot.</span></span></param>
        <param name="storageId"><span data-ttu-id="4686a-104">トラブルシューティングの結果を保存するストレージ アカウントの ID です。</span><span class="sxs-lookup"><span data-stu-id="4686a-104">The ID for the storage account to save the troubleshoot result.</span></span></param>
        <param name="storagePath"><span data-ttu-id="4686a-105">トラブルシューティングの結果を保存する blob へのパス。</span><span class="sxs-lookup"><span data-stu-id="4686a-105">The path to the blob to save the troubleshoot result in.</span></span></param>
        <summary>
            <span data-ttu-id="4686a-106">TroubleshootingParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4686a-106">Initializes a new instance of the TroubleshootingParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageId">
      <MemberSignature Language="C#" Value="public string StorageId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.TroubleshootingParameters.StorageId" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageId As String" />
      <MemberSignature Language="F#" Value="member this.StorageId : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.TroubleshootingParameters.StorageId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4686a-107">取得またはトラブルシューティングの結果を保存するストレージ アカウントの ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="4686a-107">Gets or sets the ID for the storage account to save the troubleshoot result.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoragePath">
      <MemberSignature Language="C#" Value="public string StoragePath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StoragePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.TroubleshootingParameters.StoragePath" />
      <MemberSignature Language="VB.NET" Value="Public Property StoragePath As String" />
      <MemberSignature Language="F#" Value="member this.StoragePath : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.TroubleshootingParameters.StoragePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storagePath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4686a-108">取得またはでトラブルシューティングの結果を保存する blob へのパスを設定します。</span><span class="sxs-lookup"><span data-stu-id="4686a-108">Gets or sets the path to the blob to save the troubleshoot result in.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetResourceId">
      <MemberSignature Language="C#" Value="public string TargetResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.TroubleshootingParameters.TargetResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetResourceId As String" />
      <MemberSignature Language="F#" Value="member this.TargetResourceId : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.TroubleshootingParameters.TargetResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetResourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4686a-109">取得またはトラブルシューティングを行うにターゲット リソースを設定します。</span><span class="sxs-lookup"><span data-stu-id="4686a-109">Gets or sets the target resource to troubleshoot.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.TroubleshootingParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="troubleshootingParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4686a-110">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="4686a-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4686a-111">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4686a-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>