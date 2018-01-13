<Type Name="AdvancedSchedule" FullName="Microsoft.Azure.Management.Automation.Models.AdvancedSchedule">
  <TypeSignature Language="C#" Value="public class AdvancedSchedule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AdvancedSchedule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.Models.AdvancedSchedule" />
  <TypeSignature Language="VB.NET" Value="Public Class AdvancedSchedule" />
  <TypeSignature Language="F#" Value="type AdvancedSchedule = class" />
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
            <span data-ttu-id="d0b83-101">[詳細設定] のスケジュールの作成のプロパティ。</span><span class="sxs-lookup"><span data-stu-id="d0b83-101">The properties of the create Advanced Schedule.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdvancedSchedule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.AdvancedSchedule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d0b83-102">AdvancedSchedule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d0b83-102">Initializes a new instance of the AdvancedSchedule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MonthDays">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;int&gt; MonthDays { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;int32&gt; MonthDays" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.AdvancedSchedule.MonthDays" />
      <MemberSignature Language="VB.NET" Value="Public Property MonthDays As IList(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MonthDays : System.Collections.Generic.IList&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Automation.Models.AdvancedSchedule.MonthDays" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d0b83-103">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d0b83-103">Optional.</span></span> <span data-ttu-id="d0b83-104">ジョブを実行する必要がありますの月の日です。</span><span class="sxs-lookup"><span data-stu-id="d0b83-104">Days of the month that the job should execute on.</span></span> <span data-ttu-id="d0b83-105">1 から 31 までの間でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="d0b83-105">Must be between 1 and 31.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MonthlyOccurrences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Automation.Models.AdvancedScheduleMonthlyOccurrence&gt; MonthlyOccurrences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Automation.Models.AdvancedScheduleMonthlyOccurrence&gt; MonthlyOccurrences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.AdvancedSchedule.MonthlyOccurrences" />
      <MemberSignature Language="VB.NET" Value="Public Property MonthlyOccurrences As IList(Of AdvancedScheduleMonthlyOccurrence)" />
      <MemberSignature Language="F#" Value="member this.MonthlyOccurrences : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Automation.Models.AdvancedScheduleMonthlyOccurrence&gt; with get, set" Usage="Microsoft.Azure.Management.Automation.Models.AdvancedSchedule.MonthlyOccurrences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Automation.Models.AdvancedScheduleMonthlyOccurrence&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d0b83-106">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d0b83-106">Optional.</span></span> <span data-ttu-id="d0b83-107">月内の日数の出現します。</span><span class="sxs-lookup"><span data-stu-id="d0b83-107">Occurrences of days within a month.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WeekDays">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; WeekDays { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; WeekDays" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.AdvancedSchedule.WeekDays" />
      <MemberSignature Language="VB.NET" Value="Public Property WeekDays As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.WeekDays : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Automation.Models.AdvancedSchedule.WeekDays" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d0b83-108">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d0b83-108">Optional.</span></span> <span data-ttu-id="d0b83-109">曜日上、ジョブを実行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="d0b83-109">Days of the week that the job should execute on.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>