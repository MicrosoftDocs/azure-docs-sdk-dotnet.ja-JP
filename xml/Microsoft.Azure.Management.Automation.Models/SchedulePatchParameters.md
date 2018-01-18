<Type Name="SchedulePatchParameters" FullName="Microsoft.Azure.Management.Automation.Models.SchedulePatchParameters">
  <TypeSignature Language="C#" Value="public class SchedulePatchParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SchedulePatchParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.Models.SchedulePatchParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class SchedulePatchParameters" />
  <TypeSignature Language="F#" Value="type SchedulePatchParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="782da-101">修正プログラムのスケジュール操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="782da-101">The parameters supplied to the patch schedule operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SchedulePatchParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.SchedulePatchParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="782da-102">SchedulePatchParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="782da-102">Initializes a new instance of the SchedulePatchParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SchedulePatchParameters (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.SchedulePatchParameters.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Automation.Models.SchedulePatchParameters : string -&gt; Microsoft.Azure.Management.Automation.Models.SchedulePatchParameters" Usage="new Microsoft.Azure.Management.Automation.Models.SchedulePatchParameters name" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <summary>
            <span data-ttu-id="782da-103">必須の引数で SchedulePatchParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="782da-103">Initializes a new instance of the SchedulePatchParameters class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConvertTimesFromTimeZone">
      <MemberSignature Language="C#" Value="public bool ConvertTimesFromTimeZone { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ConvertTimesFromTimeZone" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.SchedulePatchParameters.ConvertTimesFromTimeZone" />
      <MemberSignature Language="VB.NET" Value="Public Property ConvertTimesFromTimeZone As Boolean" />
      <MemberSignature Language="F#" Value="member this.ConvertTimesFromTimeZone : bool with get, set" Usage="Microsoft.Azure.Management.Automation.Models.SchedulePatchParameters.ConvertTimesFromTimeZone" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="782da-104">省略可能。</span><span class="sxs-lookup"><span data-stu-id="782da-104">Optional.</span></span> <span data-ttu-id="782da-105">時間が指定されましたが、指定されたタイム ゾーンで指定された場合は true。</span><span class="sxs-lookup"><span data-stu-id="782da-105">True if times provided are specified in the provided time zone.</span></span> <span data-ttu-id="782da-106">時刻は UTC である場合は false。</span><span class="sxs-lookup"><span data-stu-id="782da-106">False if times are in UTC.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.SchedulePatchParameters.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Automation.Models.SchedulePatchParameters.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="782da-107">必須。</span><span class="sxs-lookup"><span data-stu-id="782da-107">Required.</span></span> <span data-ttu-id="782da-108">取得またはスケジュールの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="782da-108">Gets or sets the name of the schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.Models.SchedulePatchProperties Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.Models.SchedulePatchProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.SchedulePatchParameters.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As SchedulePatchProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Management.Automation.Models.SchedulePatchProperties with get, set" Usage="Microsoft.Azure.Management.Automation.Models.SchedulePatchParameters.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.SchedulePatchProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="782da-109">省略可能。</span><span class="sxs-lookup"><span data-stu-id="782da-109">Optional.</span></span> <span data-ttu-id="782da-110">取得またはスケジュールのプロパティの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="782da-110">Gets or sets the list of schedule properties.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>