<Type Name="SoftDeleteColumnDeletionDetectionPolicy" FullName="Microsoft.Azure.Search.Models.SoftDeleteColumnDeletionDetectionPolicy">
  <TypeSignature Language="C#" Value="public class SoftDeleteColumnDeletionDetectionPolicy : Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SoftDeleteColumnDeletionDetectionPolicy extends Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.SoftDeleteColumnDeletionDetectionPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class SoftDeleteColumnDeletionDetectionPolicy&#xA;Inherits DataDeletionDetectionPolicy" />
  <TypeSignature Language="F#" Value="type SoftDeleteColumnDeletionDetectionPolicy = class&#xA;    inherit DataDeletionDetectionPolicy" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.SoftDeleteColumnDeletionDetectionPolicy")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="663bd-101">ソフト削除方針を実装するデータ削除検出ポリシーを定義します。</span><span class="sxs-lookup"><span data-stu-id="663bd-101">Defines a data deletion detection policy that implements a soft-deletion strategy.</span></span> <span data-ttu-id="663bd-102">これは、指定された「ソフト削除」列の値に基づいて項目を削除するかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="663bd-102">It determines whether an item should be deleted based on the value of a designated 'soft delete' column.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SoftDeleteColumnDeletionDetectionPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SoftDeleteColumnDeletionDetectionPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="663bd-103">SoftDeleteColumnDeletionDetectionPolicy クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="663bd-103">Initializes a new instance of the SoftDeleteColumnDeletionDetectionPolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SoftDeleteColumnDeletionDetectionPolicy (string softDeleteColumnName, object softDeleteMarkerValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string softDeleteColumnName, object softDeleteMarkerValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SoftDeleteColumnDeletionDetectionPolicy.#ctor(System.String,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (softDeleteColumnName As String, softDeleteMarkerValue As Object)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.SoftDeleteColumnDeletionDetectionPolicy : string * obj -&gt; Microsoft.Azure.Search.Models.SoftDeleteColumnDeletionDetectionPolicy" Usage="new Microsoft.Azure.Search.Models.SoftDeleteColumnDeletionDetectionPolicy (softDeleteColumnName, softDeleteMarkerValue)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="softDeleteColumnName" Type="System.String" />
        <Parameter Name="softDeleteMarkerValue" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="softDeleteColumnName">
            <span data-ttu-id="663bd-104">ソフト削除検出に使用する列の名前を指定します。</span><span class="sxs-lookup"><span data-stu-id="663bd-104">Specifies the name of the column to use for soft-deletion detection.</span></span>
            </param>
        <param name="softDeleteMarkerValue">
            <span data-ttu-id="663bd-105">削除済みとしてアイテムを識別するマーカー値を指定します。</span><span class="sxs-lookup"><span data-stu-id="663bd-105">Specifies the marker value that indentifies an item as deleted.</span></span>
            </param>
        <summary>
            <span data-ttu-id="663bd-106">必須の引数で SoftDeleteColumnDeletionDetectionPolicy クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="663bd-106">Initializes a new instance of the SoftDeleteColumnDeletionDetectionPolicy class with required arguments.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SoftDeleteColumnDeletionDetectionPolicy (string softDeleteColumnName = null, string softDeleteMarkerValue = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string softDeleteColumnName, string softDeleteMarkerValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SoftDeleteColumnDeletionDetectionPolicy.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional softDeleteColumnName As String = null, Optional softDeleteMarkerValue As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.SoftDeleteColumnDeletionDetectionPolicy : string * string -&gt; Microsoft.Azure.Search.Models.SoftDeleteColumnDeletionDetectionPolicy" Usage="new Microsoft.Azure.Search.Models.SoftDeleteColumnDeletionDetectionPolicy (softDeleteColumnName, softDeleteMarkerValue)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="softDeleteColumnName" Type="System.String" />
        <Parameter Name="softDeleteMarkerValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="softDeleteColumnName"><span data-ttu-id="663bd-107">ソフト削除検出に使用する列の名前。</span><span class="sxs-lookup"><span data-stu-id="663bd-107">The name of the column to use for soft-deletion detection.</span></span></param>
        <param name="softDeleteMarkerValue"><span data-ttu-id="663bd-108">削除済みとしてアイテムを識別するマーカー値です。</span><span class="sxs-lookup"><span data-stu-id="663bd-108">The marker value that indentifies an item as deleted.</span></span></param>
        <summary>
            <span data-ttu-id="663bd-109">SoftDeleteColumnDeletionDetectionPolicy クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="663bd-109">Initializes a new instance of the SoftDeleteColumnDeletionDetectionPolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SoftDeleteColumnName">
      <MemberSignature Language="C#" Value="public string SoftDeleteColumnName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SoftDeleteColumnName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SoftDeleteColumnDeletionDetectionPolicy.SoftDeleteColumnName" />
      <MemberSignature Language="VB.NET" Value="Public Property SoftDeleteColumnName As String" />
      <MemberSignature Language="F#" Value="member this.SoftDeleteColumnName : string with get, set" Usage="Microsoft.Azure.Search.Models.SoftDeleteColumnDeletionDetectionPolicy.SoftDeleteColumnName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="softDeleteColumnName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="663bd-110">取得またはソフト削除検出に使用する列の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="663bd-110">Gets or sets the name of the column to use for soft-deletion detection.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SoftDeleteMarkerValue">
      <MemberSignature Language="C#" Value="public string SoftDeleteMarkerValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SoftDeleteMarkerValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SoftDeleteColumnDeletionDetectionPolicy.SoftDeleteMarkerValue" />
      <MemberSignature Language="VB.NET" Value="Public Property SoftDeleteMarkerValue As String" />
      <MemberSignature Language="F#" Value="member this.SoftDeleteMarkerValue : string with get, set" Usage="Microsoft.Azure.Search.Models.SoftDeleteColumnDeletionDetectionPolicy.SoftDeleteMarkerValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="softDeleteMarkerValue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="663bd-111">取得または削除済みとしてアイテムを識別するマーカー値を設定します。</span><span class="sxs-lookup"><span data-stu-id="663bd-111">Gets or sets the marker value that indentifies an item as deleted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>