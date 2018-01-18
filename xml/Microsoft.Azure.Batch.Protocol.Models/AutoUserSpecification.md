<Type Name="AutoUserSpecification" FullName="Microsoft.Azure.Batch.Protocol.Models.AutoUserSpecification">
  <TypeSignature Language="C#" Value="public class AutoUserSpecification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AutoUserSpecification extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.AutoUserSpecification" />
  <TypeSignature Language="VB.NET" Value="Public Class AutoUserSpecification" />
  <TypeSignature Language="F#" Value="type AutoUserSpecification = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="82072-101">バッチ サービスでタスクを実行する自動ユーザー用のパラメーターを指定します。</span><span class="sxs-lookup"><span data-stu-id="82072-101">Specifies the parameters for the auto user that runs a task on the Batch service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoUserSpecification ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.AutoUserSpecification.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="82072-102">AutoUserSpecification クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="82072-102">Initializes a new instance of the AutoUserSpecification class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoUserSpecification (Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.AutoUserScope&gt; scope = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ElevationLevel&gt; elevationLevel = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.AutoUserScope&gt; scope, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.ElevationLevel&gt; elevationLevel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.AutoUserSpecification.#ctor(System.Nullable{Microsoft.Azure.Batch.Protocol.Models.AutoUserScope},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.ElevationLevel})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional scope As Nullable(Of AutoUserScope) = null, Optional elevationLevel As Nullable(Of ElevationLevel) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.AutoUserSpecification : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.AutoUserScope&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ElevationLevel&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.AutoUserSpecification" Usage="new Microsoft.Azure.Batch.Protocol.Models.AutoUserSpecification (scope, elevationLevel)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="scope" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.AutoUserScope&gt;" />
        <Parameter Name="elevationLevel" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ElevationLevel&gt;" />
      </Parameters>
      <Docs>
        <param name="scope"><span data-ttu-id="82072-103">自動ユーザーのスコープ</span><span class="sxs-lookup"><span data-stu-id="82072-103">The scope for the auto user</span></span></param>
        <param name="elevationLevel"><span data-ttu-id="82072-104">自動ユーザー昇格レベル。</span><span class="sxs-lookup"><span data-stu-id="82072-104">The elevation level of the auto user.</span></span></param>
        <summary>
            <span data-ttu-id="82072-105">AutoUserSpecification クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="82072-105">Initializes a new instance of the AutoUserSpecification class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ElevationLevel">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ElevationLevel&gt; ElevationLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.ElevationLevel&gt; ElevationLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.AutoUserSpecification.ElevationLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property ElevationLevel As Nullable(Of ElevationLevel)" />
      <MemberSignature Language="F#" Value="member this.ElevationLevel : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ElevationLevel&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.AutoUserSpecification.ElevationLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="elevationLevel")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ElevationLevel&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="82072-106">取得または自動ユーザーの昇格のレベルを設定します。</span><span class="sxs-lookup"><span data-stu-id="82072-106">Gets or sets the elevation level of the auto user.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="82072-107">nonAdmin - 自動ユーザーは、管理者特権でのアクセス権のない標準ユーザーです。</span><span class="sxs-lookup"><span data-stu-id="82072-107">nonAdmin - The auto user is a standard user without elevated access.</span></span> <span data-ttu-id="82072-108">管理 - 自動ユーザー昇格されたアクセス権を持つユーザーは、完全な管理者アクセス許可で操作を行います。</span><span class="sxs-lookup"><span data-stu-id="82072-108">admin - The auto user is a user with elevated access and operates with full Administrator permissions.</span></span> <span data-ttu-id="82072-109">既定値は、nonAdmin です。</span><span class="sxs-lookup"><span data-stu-id="82072-109">The default value is nonAdmin.</span></span> <span data-ttu-id="82072-110">使用可能な値が含まれます: 'nonAdmin'、'admin'</span><span class="sxs-lookup"><span data-stu-id="82072-110">Possible values include: 'nonAdmin', 'admin'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Scope">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.AutoUserScope&gt; Scope { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.AutoUserScope&gt; Scope" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.AutoUserSpecification.Scope" />
      <MemberSignature Language="VB.NET" Value="Public Property Scope As Nullable(Of AutoUserScope)" />
      <MemberSignature Language="F#" Value="member this.Scope : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.AutoUserScope&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.AutoUserSpecification.Scope" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="scope")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.AutoUserScope&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="82072-111">取得または設定、自動ユーザーのスコープ</span><span class="sxs-lookup"><span data-stu-id="82072-111">Gets or sets the scope for the auto user</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="82072-112">既定値はタスクです。</span><span class="sxs-lookup"><span data-stu-id="82072-112">The default value is task.</span></span> <span data-ttu-id="82072-113">使用可能な値が含まれます 'task'、'プール'。</span><span class="sxs-lookup"><span data-stu-id="82072-113">Possible values include: 'task', 'pool'</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>