<Type Name="Recurrence" FullName="Microsoft.Azure.Management.Monitor.Management.Models.Recurrence">
  <TypeSignature Language="C#" Value="public class Recurrence" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Recurrence extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.Recurrence" />
  <TypeSignature Language="VB.NET" Value="Public Class Recurrence" />
  <TypeSignature Language="F#" Value="type Recurrence = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="62ad1-101">このプロファイルを開始する繰り返しの時間。</span><span class="sxs-lookup"><span data-stu-id="62ad1-101">The repeating times at which this profile begins.</span></span> <span data-ttu-id="62ad1-102">FixedDate 要素が使用する場合は、この要素は使用されません。</span><span class="sxs-lookup"><span data-stu-id="62ad1-102">This element is not used if the FixedDate element is used.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Recurrence ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.Recurrence.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="62ad1-103">定期的なクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="62ad1-103">Initializes a new instance of the Recurrence class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Recurrence (Microsoft.Azure.Management.Monitor.Management.Models.RecurrenceFrequency frequency, Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule schedule);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Monitor.Management.Models.RecurrenceFrequency frequency, class Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule schedule) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.Recurrence.#ctor(Microsoft.Azure.Management.Monitor.Management.Models.RecurrenceFrequency,Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (frequency As RecurrenceFrequency, schedule As RecurrentSchedule)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.Recurrence : Microsoft.Azure.Management.Monitor.Management.Models.RecurrenceFrequency * Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule -&gt; Microsoft.Azure.Management.Monitor.Management.Models.Recurrence" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.Recurrence (frequency, schedule)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="frequency" Type="Microsoft.Azure.Management.Monitor.Management.Models.RecurrenceFrequency" />
        <Parameter Name="schedule" Type="Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule" />
      </Parameters>
      <Docs>
        <param name="frequency"><span data-ttu-id="62ad1-104">繰り返しの頻度。</span><span class="sxs-lookup"><span data-stu-id="62ad1-104">the recurrence frequency.</span></span> <span data-ttu-id="62ad1-105">どのくらいの頻度、スケジュール プロファイル反映されます。</span><span class="sxs-lookup"><span data-stu-id="62ad1-105">How often the schedule profile should take effect.</span></span> <span data-ttu-id="62ad1-106">この値は、週、つまり、毎週同じセットのプロファイルになりますである必要があります。</span><span class="sxs-lookup"><span data-stu-id="62ad1-106">This value must be Week, meaning each week will have the same set of profiles.</span></span> <span data-ttu-id="62ad1-107">使用可能な値が含まれます 'None'、'2'、'Minute'、'Hour'、'日'、'週'、'Month'、'Year'。</span><span class="sxs-lookup"><span data-stu-id="62ad1-107">Possible values include: 'None', 'Second', 'Minute', 'Hour', 'Day', 'Week', 'Month', 'Year'</span></span></param>
        <param name="schedule"><span data-ttu-id="62ad1-108">プロファイルを開始するときのスケジュールに関する制約。</span><span class="sxs-lookup"><span data-stu-id="62ad1-108">the scheduling constraints for when the profile begins.</span></span></param>
        <summary>
            <span data-ttu-id="62ad1-109">定期的なクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="62ad1-109">Initializes a new instance of the Recurrence class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Frequency">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.RecurrenceFrequency Frequency { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Monitor.Management.Models.RecurrenceFrequency Frequency" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.Recurrence.Frequency" />
      <MemberSignature Language="VB.NET" Value="Public Property Frequency As RecurrenceFrequency" />
      <MemberSignature Language="F#" Value="member this.Frequency : Microsoft.Azure.Management.Monitor.Management.Models.RecurrenceFrequency with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.Recurrence.Frequency" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="frequency")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.RecurrenceFrequency</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="62ad1-110">取得または繰り返しの頻度を設定します。</span><span class="sxs-lookup"><span data-stu-id="62ad1-110">Gets or sets the recurrence frequency.</span></span> <span data-ttu-id="62ad1-111">どのくらいの頻度、スケジュール プロファイル反映されます。</span><span class="sxs-lookup"><span data-stu-id="62ad1-111">How often the schedule profile should take effect.</span></span> <span data-ttu-id="62ad1-112">この値は、週、つまり、毎週同じセットのプロファイルになりますである必要があります。</span><span class="sxs-lookup"><span data-stu-id="62ad1-112">This value must be Week, meaning each week will have the same set of profiles.</span></span> <span data-ttu-id="62ad1-113">使用可能な値が含まれます 'None'、'2'、'Minute'、'Hour'、'日'、'週'、'Month'、'Year'。</span><span class="sxs-lookup"><span data-stu-id="62ad1-113">Possible values include: 'None', 'Second', 'Minute', 'Hour', 'Day', 'Week', 'Month', 'Year'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Schedule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule Schedule { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule Schedule" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.Recurrence.Schedule" />
      <MemberSignature Language="VB.NET" Value="Public Property Schedule As RecurrentSchedule" />
      <MemberSignature Language="F#" Value="member this.Schedule : Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.Recurrence.Schedule" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="schedule")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="62ad1-114">取得またはプロファイルを開始するときのスケジュールに関する制約を設定します。</span><span class="sxs-lookup"><span data-stu-id="62ad1-114">Gets or sets the scheduling constraints for when the profile begins.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.Recurrence.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="recurrence.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="62ad1-115">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="62ad1-115">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="62ad1-116">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="62ad1-116">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>