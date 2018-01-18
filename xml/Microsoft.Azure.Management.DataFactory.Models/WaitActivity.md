<Type Name="WaitActivity" FullName="Microsoft.Azure.Management.DataFactory.Models.WaitActivity">
  <TypeSignature Language="C#" Value="public class WaitActivity : Microsoft.Azure.Management.DataFactory.Models.ControlActivity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WaitActivity extends Microsoft.Azure.Management.DataFactory.Models.ControlActivity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.WaitActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class WaitActivity&#xA;Inherits ControlActivity" />
  <TypeSignature Language="F#" Value="type WaitActivity = class&#xA;    inherit ControlActivity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.ControlActivity</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Wait")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="1e87d-101">このアクティビティは、指定した期間のパイプラインの実行を中断します。</span><span class="sxs-lookup"><span data-stu-id="1e87d-101">This activity suspends pipeline execution for the specified interval.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WaitActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.WaitActivity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1e87d-102">WaitActivity クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1e87d-102">Initializes a new instance of the WaitActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WaitActivity (string name, int waitTimeInSeconds, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, int32 waitTimeInSeconds, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.WaitActivity.#ctor(System.String,System.Int32,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.ActivityDependency})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, waitTimeInSeconds As Integer, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional dependsOn As IList(Of ActivityDependency) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.WaitActivity : string * int * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.WaitActivity" Usage="new Microsoft.Azure.Management.DataFactory.Models.WaitActivity (name, waitTimeInSeconds, additionalProperties, description, dependsOn)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="waitTimeInSeconds" Type="System.Int32" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="dependsOn" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="1e87d-103">アクティビティ名。</span><span class="sxs-lookup"><span data-stu-id="1e87d-103">Activity name.</span></span></param>
        <param name="waitTimeInSeconds"><span data-ttu-id="1e87d-104">実行時間 (秒) です。</span><span class="sxs-lookup"><span data-stu-id="1e87d-104">Duration in seconds.</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="1e87d-105">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="1e87d-105">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="description"><span data-ttu-id="1e87d-106">アクティビティの説明です。</span><span class="sxs-lookup"><span data-stu-id="1e87d-106">Activity description.</span></span></param>
        <param name="dependsOn"><span data-ttu-id="1e87d-107">アクティビティは、条件によって異なります。</span><span class="sxs-lookup"><span data-stu-id="1e87d-107">Activity depends on condition.</span></span></param>
        <summary>
            <span data-ttu-id="1e87d-108">WaitActivity クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1e87d-108">Initializes a new instance of the WaitActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.WaitActivity.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="waitActivity.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1e87d-109">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="1e87d-109">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1e87d-110">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1e87d-110">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="WaitTimeInSeconds">
      <MemberSignature Language="C#" Value="public int WaitTimeInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 WaitTimeInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.WaitActivity.WaitTimeInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property WaitTimeInSeconds As Integer" />
      <MemberSignature Language="F#" Value="member this.WaitTimeInSeconds : int with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.WaitActivity.WaitTimeInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.waitTimeInSeconds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e87d-111">取得または期間を秒単位で設定します。</span><span class="sxs-lookup"><span data-stu-id="1e87d-111">Gets or sets duration in seconds.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>