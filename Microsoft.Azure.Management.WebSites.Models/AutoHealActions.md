<Type Name="AutoHealActions" FullName="Microsoft.Azure.Management.WebSites.Models.AutoHealActions">
  <TypeSignature Language="C#" Value="public class AutoHealActions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AutoHealActions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.AutoHealActions" />
  <TypeSignature Language="VB.NET" Value="Public Class AutoHealActions" />
  <TypeSignature Language="F#" Value="type AutoHealActions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            アクションでを実行する対象のルールがトリガーされたときにモジュールの自動-回復させます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoHealActions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.AutoHealActions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            AutoHealActions クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoHealActions (Nullable&lt;Microsoft.Azure.Management.WebSites.Models.AutoHealActionType&gt; actionType = null, Microsoft.Azure.Management.WebSites.Models.AutoHealCustomAction customAction = null, string minProcessExecutionTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.AutoHealActionType&gt; actionType, class Microsoft.Azure.Management.WebSites.Models.AutoHealCustomAction customAction, string minProcessExecutionTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.AutoHealActions.#ctor(System.Nullable{Microsoft.Azure.Management.WebSites.Models.AutoHealActionType},Microsoft.Azure.Management.WebSites.Models.AutoHealCustomAction,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional actionType As Nullable(Of AutoHealActionType) = null, Optional customAction As AutoHealCustomAction = null, Optional minProcessExecutionTime As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.AutoHealActions : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.AutoHealActionType&gt; * Microsoft.Azure.Management.WebSites.Models.AutoHealCustomAction * string -&gt; Microsoft.Azure.Management.WebSites.Models.AutoHealActions" Usage="new Microsoft.Azure.Management.WebSites.Models.AutoHealActions (actionType, customAction, minProcessExecutionTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="actionType" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.AutoHealActionType&gt;" />
        <Parameter Name="customAction" Type="Microsoft.Azure.Management.WebSites.Models.AutoHealCustomAction" />
        <Parameter Name="minProcessExecutionTime" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="actionType">実行する定義済みのアクション。 使用可能な値が含まれます: 'ごみ'、'LogEvent'、'CustomAction'</param>
        <param name="customAction">実行するカスタム アクション。</param>
        <param name="minProcessExecutionTime">最小時間プロセスで、操作を実行する前に実行する必要があります。</param>
        <summary>
            AutoHealActions クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActionType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.AutoHealActionType&gt; ActionType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.AutoHealActionType&gt; ActionType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AutoHealActions.ActionType" />
      <MemberSignature Language="VB.NET" Value="Public Property ActionType As Nullable(Of AutoHealActionType)" />
      <MemberSignature Language="F#" Value="member this.ActionType : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.AutoHealActionType&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AutoHealActions.ActionType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="actionType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.AutoHealActionType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または実行する定義済みのアクションを設定します。 使用可能な値が含まれます: 'ごみ'、'LogEvent'、'CustomAction'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomAction">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.AutoHealCustomAction CustomAction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.AutoHealCustomAction CustomAction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AutoHealActions.CustomAction" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomAction As AutoHealCustomAction" />
      <MemberSignature Language="F#" Value="member this.CustomAction : Microsoft.Azure.Management.WebSites.Models.AutoHealCustomAction with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AutoHealActions.CustomAction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="customAction")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.AutoHealCustomAction</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または実行するカスタム アクションを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinProcessExecutionTime">
      <MemberSignature Language="C#" Value="public string MinProcessExecutionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MinProcessExecutionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AutoHealActions.MinProcessExecutionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property MinProcessExecutionTime As String" />
      <MemberSignature Language="F#" Value="member this.MinProcessExecutionTime : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AutoHealActions.MinProcessExecutionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="minProcessExecutionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の最小の時間が、操作を実行する前に、プロセスを実行する必要があります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>