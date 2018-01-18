<Type Name="GeometryValidationResult" FullName="Microsoft.Azure.Documents.Spatial.GeometryValidationResult">
  <TypeSignature Language="C#" Value="public class GeometryValidationResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit GeometryValidationResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Spatial.GeometryValidationResult" />
  <TypeSignature Language="VB.NET" Value="Public Class GeometryValidationResult" />
  <TypeSignature Language="F#" Value="type GeometryValidationResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject(Newtonsoft.Json.MemberSerialization.OptIn)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para>
            <span data-ttu-id="ecae0-101">値を返す<see cref="M:Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions.IsValidDetailed(Microsoft.Azure.Documents.Spatial.Geometry)" />Cosmos DB の Azure サービスにします。</span><span class="sxs-lookup"><span data-stu-id="ecae0-101">Return value of <see cref="M:Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions.IsValidDetailed(Microsoft.Azure.Documents.Spatial.Geometry)" /> in the Azure Cosmos DB service.</span></span>
            </para>
      <para>
            <span data-ttu-id="ecae0-102">詳細な説明、geometyr が有効な理由にはが含まれています。</span><span class="sxs-lookup"><span data-stu-id="ecae0-102">Contains detailed description why a geometyr is invalid.</span></span>
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GeometryValidationResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.GeometryValidationResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsValid">
      <MemberSignature Language="C#" Value="public bool IsValid { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsValid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.GeometryValidationResult.IsValid" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsValid As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsValid : bool" Usage="Microsoft.Azure.Documents.Spatial.GeometryValidationResult.IsValid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty("valid", Order=0, Required=Newtonsoft.Json.Required.Always)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ecae0-103">示す値を返すかどうかを geometry<see cref="M:Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions.IsValidDetailed(Microsoft.Azure.Documents.Spatial.Geometry)" />が呼び出されましたが有効か、Azure Cosmos DB ではなくサービスを提供します。</span><span class="sxs-lookup"><span data-stu-id="ecae0-103">Returns a value indicating whether geometry for which <see cref="M:Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions.IsValidDetailed(Microsoft.Azure.Documents.Spatial.Geometry)" /> was called is valid or not in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
          <span data-ttu-id="ecae0-104"><c>true</c>場合を geometry<see cref="M:Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions.IsValidDetailed(Microsoft.Azure.Documents.Spatial.Geometry)" />が呼び出されましたが有効です。</span><span class="sxs-lookup"><span data-stu-id="ecae0-104"><c>true</c> if geometry for which <see cref="M:Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions.IsValidDetailed(Microsoft.Azure.Documents.Spatial.Geometry)" /> was called is valid.</span></span> <span data-ttu-id="ecae0-105"><c>false</c>それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="ecae0-105"><c>false</c> otherwise.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reason">
      <MemberSignature Language="C#" Value="public string Reason { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Reason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.GeometryValidationResult.Reason" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Reason As String" />
      <MemberSignature Language="F#" Value="member this.Reason : string" Usage="Microsoft.Azure.Documents.Spatial.GeometryValidationResult.Reason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty("reason", Order=1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ecae0-106">Geometry が有効でない場合は、Azure Cosmos DB サービスの詳細な理由を返します。</span><span class="sxs-lookup"><span data-stu-id="ecae0-106">If geometry is invalid, returns detailed reason in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="ecae0-107">Geometry が有効な理由の説明。</span><span class="sxs-lookup"><span data-stu-id="ecae0-107">Description why a geometry is invalid.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>