<Type Name="TaskFailureInformation" FullName="Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation">
  <TypeSignature Language="C#" Value="public class TaskFailureInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskFailureInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskFailureInformation" />
  <TypeSignature Language="F#" Value="type TaskFailureInformation = class" />
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
            タスクの失敗に関する情報です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskFailureInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation.#ctor" />
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
            TaskFailureInformation クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskFailureInformation (Microsoft.Azure.Batch.Protocol.Models.ErrorCategory category, string code = null, string message = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; details = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Batch.Protocol.Models.ErrorCategory category, string code, string message, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; details) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation.#ctor(Microsoft.Azure.Batch.Protocol.Models.ErrorCategory,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.NameValuePair})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (category As ErrorCategory, Optional code As String = null, Optional message As String = null, Optional details As IList(Of NameValuePair) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation : Microsoft.Azure.Batch.Protocol.Models.ErrorCategory * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation" Usage="new Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation (category, code, message, details)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="category" Type="Microsoft.Azure.Batch.Protocol.Models.ErrorCategory" />
        <Parameter Name="code" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="details" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt;" />
      </Parameters>
      <Docs>
        <param name="category">タスク エラーのカテゴリ。</param>
        <param name="code">タスク エラーの識別子。 コードは変化せず、プログラムでの使用を目的としています。</param>
        <param name="message">ユーザー インターフェイスでの表示に適したするもので、タスクのエラーを説明するメッセージ。</param>
        <param name="details">エラーに関連する追加の詳細の一覧。</param>
        <summary>
            TaskFailureInformation クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Category">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ErrorCategory Category { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Protocol.Models.ErrorCategory Category" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation.Category" />
      <MemberSignature Language="VB.NET" Value="Public Property Category As ErrorCategory" />
      <MemberSignature Language="F#" Value="member this.Category : Microsoft.Azure.Batch.Protocol.Models.ErrorCategory with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation.Category" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="category")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ErrorCategory</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはタスク エラーのカテゴリを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            使用可能な値が含まれます: 'userError'、'serverError'
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation.Code" />
      <MemberSignature Language="VB.NET" Value="Public Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="code")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはタスク エラーの識別子を設定します。 コードは変化せず、プログラムでの使用を目的としています。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Details">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; Details { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; Details" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation.Details" />
      <MemberSignature Language="VB.NET" Value="Public Property Details As IList(Of NameValuePair)" />
      <MemberSignature Language="F#" Value="member this.Details : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation.Details" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="details")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはエラーに関連する追加の詳細の一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定するユーザー インターフェイスでの表示に適したもので、タスクのエラーを説明するメッセージ。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="taskFailureInformation.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>