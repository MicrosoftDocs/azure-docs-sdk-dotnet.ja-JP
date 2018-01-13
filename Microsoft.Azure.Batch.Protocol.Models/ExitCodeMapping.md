<Type Name="ExitCodeMapping" FullName="Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping">
  <TypeSignature Language="C#" Value="public class ExitCodeMapping" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExitCodeMapping extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping" />
  <TypeSignature Language="VB.NET" Value="Public Class ExitCodeMapping" />
  <TypeSignature Language="F#" Value="type ExitCodeMapping = class" />
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
            方法は、バッチ サービスで、タスクが、特定の終了コードで終了したかどうかを応答します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExitCodeMapping ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping.#ctor" />
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
            ExitCodeMapping クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExitCodeMapping (int code, Microsoft.Azure.Batch.Protocol.Models.ExitOptions exitOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 code, class Microsoft.Azure.Batch.Protocol.Models.ExitOptions exitOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping.#ctor(System.Int32,Microsoft.Azure.Batch.Protocol.Models.ExitOptions)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping : int * Microsoft.Azure.Batch.Protocol.Models.ExitOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping" Usage="new Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping (code, exitOptions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="code" Type="System.Int32" />
        <Parameter Name="exitOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ExitOptions" />
      </Parameters>
      <Docs>
        <param name="code">プロセス終了コード。</param>
        <param name="exitOptions">方法は、バッチ サービスで、タスクがこの終了コードで終了したかどうかを応答します。</param>
        <summary>
            ExitCodeMapping クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public int Code { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping.Code" />
      <MemberSignature Language="VB.NET" Value="Public Property Code As Integer" />
      <MemberSignature Language="F#" Value="member this.Code : int with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping.Code" />
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
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプロセス終了コードを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitOptions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ExitOptions ExitOptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.ExitOptions ExitOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping.ExitOptions" />
      <MemberSignature Language="VB.NET" Value="Public Property ExitOptions As ExitOptions" />
      <MemberSignature Language="F#" Value="member this.ExitOptions : Microsoft.Azure.Batch.Protocol.Models.ExitOptions with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping.ExitOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="exitOptions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ExitOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または終了コードはこのタスクが終了した場合、バッチ サービスの応答方法を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="exitCodeMapping.Validate " />
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