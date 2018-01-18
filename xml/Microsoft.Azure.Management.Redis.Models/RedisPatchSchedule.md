<Type Name="RedisPatchSchedule" FullName="Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule">
  <TypeSignature Language="C#" Value="public class RedisPatchSchedule : Microsoft.Azure.Management.Redis.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RedisPatchSchedule extends Microsoft.Azure.Management.Redis.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule" />
  <TypeSignature Language="VB.NET" Value="Public Class RedisPatchSchedule&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type RedisPatchSchedule = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.Redis.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="d5cec-101">Redis cache の修正プログラムのスケジュールを put/get に対する応答です。</span><span class="sxs-lookup"><span data-stu-id="d5cec-101">Response to put/get patch schedules for Redis cache.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RedisPatchSchedule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d5cec-102">RedisPatchSchedule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d5cec-102">Initializes a new instance of the RedisPatchSchedule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RedisPatchSchedule (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Redis.Models.ScheduleEntry&gt; scheduleEntries, string id = null, string name = null, string type = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Redis.Models.ScheduleEntry&gt; scheduleEntries, string id, string name, string type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.Redis.Models.ScheduleEntry},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (scheduleEntries As IList(Of ScheduleEntry), Optional id As String = null, Optional name As String = null, Optional type As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Redis.Models.ScheduleEntry&gt; * string * string * string -&gt; Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule" Usage="new Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule (scheduleEntries, id, name, type)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="scheduleEntries" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Redis.Models.ScheduleEntry&gt;" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scheduleEntries"><span data-ttu-id="d5cec-103">Redis cache の修正プログラムのスケジュールの一覧です。</span><span class="sxs-lookup"><span data-stu-id="d5cec-103">List of patch schedules for a Redis cache.</span></span></param>
        <param name="id"><span data-ttu-id="d5cec-104">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="d5cec-104">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="d5cec-105">リソース名。</span><span class="sxs-lookup"><span data-stu-id="d5cec-105">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="d5cec-106">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="d5cec-106">Resource type.</span></span></param>
        <summary>
            <span data-ttu-id="d5cec-107">RedisPatchSchedule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d5cec-107">Initializes a new instance of the RedisPatchSchedule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleEntries">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Redis.Models.ScheduleEntry&gt; ScheduleEntries { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Redis.Models.ScheduleEntry&gt; ScheduleEntries" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule.ScheduleEntries" />
      <MemberSignature Language="VB.NET" Value="Public Property ScheduleEntries As IList(Of ScheduleEntry)" />
      <MemberSignature Language="F#" Value="member this.ScheduleEntries : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Redis.Models.ScheduleEntry&gt; with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule.ScheduleEntries" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.scheduleEntries")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Redis.Models.ScheduleEntry&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d5cec-108">取得または Redis キャッシュの更新プログラムのスケジュールの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="d5cec-108">Gets or sets list of patch schedules for a Redis cache.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="redisPatchSchedule.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d5cec-109">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="d5cec-109">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d5cec-110">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d5cec-110">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>