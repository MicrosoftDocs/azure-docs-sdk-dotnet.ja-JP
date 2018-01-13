<Type Name="AutoScaleRunError" FullName="Microsoft.Azure.Management.Batch.Models.AutoScaleRunError">
  <TypeSignature Language="C#" Value="public class AutoScaleRunError" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AutoScaleRunError extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.AutoScaleRunError" />
  <TypeSignature Language="VB.NET" Value="Public Class AutoScaleRunError" />
  <TypeSignature Language="F#" Value="type AutoScaleRunError = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            エラーが発生したときにプールを自動スケールします。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoScaleRunError ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.AutoScaleRunError.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            AutoScaleRunError クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoScaleRunError (string code, string message, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.AutoScaleRunError&gt; details = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string code, string message, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.AutoScaleRunError&gt; details) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.AutoScaleRunError.#ctor(System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Batch.Models.AutoScaleRunError})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (code As String, message As String, Optional details As IList(Of AutoScaleRunError) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.AutoScaleRunError : string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.AutoScaleRunError&gt; -&gt; Microsoft.Azure.Management.Batch.Models.AutoScaleRunError" Usage="new Microsoft.Azure.Management.Batch.Models.AutoScaleRunError (code, message, details)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="code" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="details" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.AutoScaleRunError&gt;" />
      </Parameters>
      <Docs>
        <param name="code">エラーの識別子。 コードは変化せず、プログラムでの使用を目的としています。</param>
        <param name="message">ユーザー インターフェイスでの表示に適したするもので、エラーを説明するメッセージ。</param>
        <param name="details">エラーの詳細を追加します。</param>
        <summary>
            AutoScaleRunError クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.AutoScaleRunError.Code" />
      <MemberSignature Language="VB.NET" Value="Public Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.AutoScaleRunError.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
            取得または設定エラーの識別子。 コードは変化せず、プログラムでの使用を目的としています。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Details">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.AutoScaleRunError&gt; Details { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.AutoScaleRunError&gt; Details" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.AutoScaleRunError.Details" />
      <MemberSignature Language="VB.NET" Value="Public Property Details As IList(Of AutoScaleRunError)" />
      <MemberSignature Language="F#" Value="member this.Details : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.AutoScaleRunError&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.AutoScaleRunError.Details" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="details")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.AutoScaleRunError&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはエラーに関する追加情報を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.AutoScaleRunError.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.AutoScaleRunError.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
            取得または設定するユーザー インターフェイスでの表示に適したもので、エラーを説明するメッセージ。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.AutoScaleRunError.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="autoScaleRunError.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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