<Type Name="ActivityLogAlertActionList" FullName="Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionList">
  <TypeSignature Language="C#" Value="public class ActivityLogAlertActionList" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ActivityLogAlertActionList extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionList" />
  <TypeSignature Language="VB.NET" Value="Public Class ActivityLogAlertActionList" />
  <TypeSignature Language="F#" Value="type ActivityLogAlertActionList = class" />
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
            <span data-ttu-id="940c0-101">アクティビティ ログ アラート アクションの一覧。</span><span class="sxs-lookup"><span data-stu-id="940c0-101">A list of activity log alert actions.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActivityLogAlertActionList ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionList.#ctor" />
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
            <span data-ttu-id="940c0-102">ActivityLogAlertActionList クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="940c0-102">Initializes a new instance of the ActivityLogAlertActionList class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActivityLogAlertActionList (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionGroup&gt; actionGroups = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionGroup&gt; actionGroups) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionList.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionGroup})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional actionGroups As IList(Of ActivityLogAlertActionGroup) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionList : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionGroup&gt; -&gt; Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionList" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionList actionGroups" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="actionGroups" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionGroup&gt;" />
      </Parameters>
      <Docs>
        <param name="actionGroups"><span data-ttu-id="940c0-103">アクティビティ ログ アラートの一覧。</span><span class="sxs-lookup"><span data-stu-id="940c0-103">The list of activity log alerts.</span></span></param>
        <summary>
            <span data-ttu-id="940c0-104">ActivityLogAlertActionList クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="940c0-104">Initializes a new instance of the ActivityLogAlertActionList class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActionGroups">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionGroup&gt; ActionGroups { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionGroup&gt; ActionGroups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionList.ActionGroups" />
      <MemberSignature Language="VB.NET" Value="Public Property ActionGroups As IList(Of ActivityLogAlertActionGroup)" />
      <MemberSignature Language="F#" Value="member this.ActionGroups : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionGroup&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionList.ActionGroups" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="actionGroups")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionGroup&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="940c0-105">取得またはログ アラート アクティビティの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="940c0-105">Gets or sets the list of activity log alerts.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>