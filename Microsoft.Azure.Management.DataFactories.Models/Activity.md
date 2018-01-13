<Type Name="Activity" FullName="Microsoft.Azure.Management.DataFactories.Models.Activity">
  <TypeSignature Language="C#" Value="public class Activity : Microsoft.Azure.Management.DataFactories.Models.AdfResourceProperties&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityTypeProperties,Microsoft.Azure.Management.DataFactories.Models.GenericActivity&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Activity extends Microsoft.Azure.Management.DataFactories.Models.AdfResourceProperties`2&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityTypeProperties, class Microsoft.Azure.Management.DataFactories.Models.GenericActivity&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.Activity" />
  <TypeSignature Language="VB.NET" Value="Public Class Activity&#xA;Inherits AdfResourceProperties(Of ActivityTypeProperties, GenericActivity)" />
  <TypeSignature Language="F#" Value="type Activity = class&#xA;    inherit AdfResourceProperties&lt;ActivityTypeProperties, GenericActivity&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.AdfResourceProperties&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityTypeProperties,Microsoft.Azure.Management.DataFactories.Models.GenericActivity&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TExtensibleTypeProperties">Microsoft.Azure.Management.DataFactories.Models.ActivityTypeProperties</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TGenericTypeProperties">Microsoft.Azure.Management.DataFactories.Models.GenericActivity</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c0427-101">パイプラインのアクティビティ。</span><span class="sxs-lookup"><span data-stu-id="c0427-101">A pipeline activity.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Activity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.Activity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Activity (Microsoft.Azure.Management.DataFactories.Models.ActivityTypeProperties typeProperties);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.DataFactories.Models.ActivityTypeProperties typeProperties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.Activity.#ctor(Microsoft.Azure.Management.DataFactories.Models.ActivityTypeProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (typeProperties As ActivityTypeProperties)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.Activity : Microsoft.Azure.Management.DataFactories.Models.ActivityTypeProperties -&gt; Microsoft.Azure.Management.DataFactories.Models.Activity" Usage="new Microsoft.Azure.Management.DataFactories.Models.Activity typeProperties" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="typeProperties" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityTypeProperties" />
      </Parameters>
      <Docs>
        <param name="typeProperties">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Activity (Microsoft.Azure.Management.DataFactories.Models.GenericActivity typeProperties, string typeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.DataFactories.Models.GenericActivity typeProperties, string typeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.Activity.#ctor(Microsoft.Azure.Management.DataFactories.Models.GenericActivity,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (typeProperties As GenericActivity, typeName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.Activity : Microsoft.Azure.Management.DataFactories.Models.GenericActivity * string -&gt; Microsoft.Azure.Management.DataFactories.Models.Activity" Usage="new Microsoft.Azure.Management.DataFactories.Models.Activity (typeProperties, typeName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="typeProperties" Type="Microsoft.Azure.Management.DataFactories.Models.GenericActivity" />
        <Parameter Name="typeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="typeProperties">To be added.</param>
        <param name="typeName">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.Activity.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.Activity.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0427-102">アクティビティの説明です。</span><span class="sxs-lookup"><span data-stu-id="c0427-102">Activity description.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Inputs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Common.Models.ActivityInput&gt; Inputs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.ActivityInput&gt; Inputs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.Activity.Inputs" />
      <MemberSignature Language="VB.NET" Value="Public Property Inputs As IList(Of ActivityInput)" />
      <MemberSignature Language="F#" Value="member this.Inputs : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Common.Models.ActivityInput&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.Activity.Inputs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Common.Models.ActivityInput&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0427-103">アクティビティの入力します。</span><span class="sxs-lookup"><span data-stu-id="c0427-103">Activity inputs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinkedServiceName">
      <MemberSignature Language="C#" Value="public string LinkedServiceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LinkedServiceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.Activity.LinkedServiceName" />
      <MemberSignature Language="VB.NET" Value="Public Property LinkedServiceName As String" />
      <MemberSignature Language="F#" Value="member this.LinkedServiceName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.Activity.LinkedServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0427-104">アクティビティが実行されているリンクされたサービスの名前です。</span><span class="sxs-lookup"><span data-stu-id="c0427-104">Name of the linked service where the Activity runs.</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.Activity.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.Activity.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0427-105">アクティビティ名。</span><span class="sxs-lookup"><span data-stu-id="c0427-105">Activity name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Outputs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Common.Models.ActivityOutput&gt; Outputs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.ActivityOutput&gt; Outputs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.Activity.Outputs" />
      <MemberSignature Language="VB.NET" Value="Public Property Outputs As IList(Of ActivityOutput)" />
      <MemberSignature Language="F#" Value="member this.Outputs : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Common.Models.ActivityOutput&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.Activity.Outputs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Common.Models.ActivityOutput&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0427-106">アクティビティの出力です。</span><span class="sxs-lookup"><span data-stu-id="c0427-106">Activity outputs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Policy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.Common.Models.ActivityPolicy Policy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Common.Models.ActivityPolicy Policy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.Activity.Policy" />
      <MemberSignature Language="VB.NET" Value="Public Property Policy As ActivityPolicy" />
      <MemberSignature Language="F#" Value="member this.Policy : Microsoft.Azure.Management.DataFactories.Common.Models.ActivityPolicy with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.Activity.Policy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Common.Models.ActivityPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0427-107">アクティビティ ポリシー。</span><span class="sxs-lookup"><span data-stu-id="c0427-107">Activity policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Scheduler">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.Common.Models.Scheduler Scheduler { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Common.Models.Scheduler Scheduler" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.Activity.Scheduler" />
      <MemberSignature Language="VB.NET" Value="Public Property Scheduler As Scheduler" />
      <MemberSignature Language="F#" Value="member this.Scheduler : Microsoft.Azure.Management.DataFactories.Common.Models.Scheduler with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.Activity.Scheduler" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Common.Models.Scheduler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0427-108">省略可能。</span><span class="sxs-lookup"><span data-stu-id="c0427-108">Optional.</span></span> <span data-ttu-id="c0427-109">アクティビティのスケジューラー。</span><span class="sxs-lookup"><span data-stu-id="c0427-109">Scheduler of the activity.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>