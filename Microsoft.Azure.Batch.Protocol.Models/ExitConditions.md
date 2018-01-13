<Type Name="ExitConditions" FullName="Microsoft.Azure.Batch.Protocol.Models.ExitConditions">
  <TypeSignature Language="C#" Value="public class ExitConditions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExitConditions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ExitConditions" />
  <TypeSignature Language="VB.NET" Value="Public Class ExitConditions" />
  <TypeSignature Language="F#" Value="type ExitConditions = class" />
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
            タスクが完了したときに、バッチ サービスの応答方法を指定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExitConditions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ExitConditions.#ctor" />
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
            ExitConditions クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExitConditions (System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping&gt; exitCodes = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping&gt; exitCodeRanges = null, Microsoft.Azure.Batch.Protocol.Models.ExitOptions preProcessingError = null, Microsoft.Azure.Batch.Protocol.Models.ExitOptions fileUploadError = null, Microsoft.Azure.Batch.Protocol.Models.ExitOptions defaultProperty = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping&gt; exitCodes, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping&gt; exitCodeRanges, class Microsoft.Azure.Batch.Protocol.Models.ExitOptions preProcessingError, class Microsoft.Azure.Batch.Protocol.Models.ExitOptions fileUploadError, class Microsoft.Azure.Batch.Protocol.Models.ExitOptions defaultProperty) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ExitConditions.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping},Microsoft.Azure.Batch.Protocol.Models.ExitOptions,Microsoft.Azure.Batch.Protocol.Models.ExitOptions,Microsoft.Azure.Batch.Protocol.Models.ExitOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional exitCodes As IList(Of ExitCodeMapping) = null, Optional exitCodeRanges As IList(Of ExitCodeRangeMapping) = null, Optional preProcessingError As ExitOptions = null, Optional fileUploadError As ExitOptions = null, Optional defaultProperty As ExitOptions = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.ExitConditions : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping&gt; * Microsoft.Azure.Batch.Protocol.Models.ExitOptions * Microsoft.Azure.Batch.Protocol.Models.ExitOptions * Microsoft.Azure.Batch.Protocol.Models.ExitOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.ExitConditions" Usage="new Microsoft.Azure.Batch.Protocol.Models.ExitConditions (exitCodes, exitCodeRanges, preProcessingError, fileUploadError, defaultProperty)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="exitCodes" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping&gt;" />
        <Parameter Name="exitCodeRanges" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping&gt;" />
        <Parameter Name="preProcessingError" Type="Microsoft.Azure.Batch.Protocol.Models.ExitOptions" />
        <Parameter Name="fileUploadError" Type="Microsoft.Azure.Batch.Protocol.Models.ExitOptions" />
        <Parameter Name="defaultProperty" Type="Microsoft.Azure.Batch.Protocol.Models.ExitOptions" />
      </Parameters>
      <Docs>
        <param name="exitCodes">個々 のタスクの終了コードと、バッチ サービスがそれらに応答する方法の一覧です。</param>
        <param name="exitCodeRanges">タスクの範囲の終了コードと、バッチ サービスがそれらに応答する方法の一覧です。</param>
        <param name="preProcessingError">バッチ サービスの応答方法、タスクがエラーのための開始に失敗したかどうか。</param>
        <param name="fileUploadError">方法ファイルのアップロード エラーが発生した場合は、バッチ サービスが応答する必要があります。</param>
        <param name="defaultProperty">バッチ サービスの応答方法、他のプロパティのいずれかでカバーされない終了条件によって、タスクが失敗した場合。</param>
        <summary>
            ExitConditions クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultProperty">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ExitOptions DefaultProperty { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.ExitOptions DefaultProperty" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ExitConditions.DefaultProperty" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultProperty As ExitOptions" />
      <MemberSignature Language="F#" Value="member this.DefaultProperty : Microsoft.Azure.Batch.Protocol.Models.ExitOptions with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ExitConditions.DefaultProperty" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="default")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ExitOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはその他のプロパティのいずれかでカバーされない終了条件によって、タスクが失敗した場合、バッチ サービスの応答方法を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            この値は、タスクが終了した場合、exitCodes または exitCodeRanges コレクションに表示されていない 0 以外の終了コード、preProcessingError プロパティが存在しない場合に、処理前のエラーまたはファイルのアップロード エラー fileUploadError プロパティが存在しない場合に使用されます。 終了コード 0 で、既定以外の動作を実行する場合に、exitCodes または exitCodeRanges のコレクションを使用して明示的にそれを一覧表示する必要があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitCodeRanges">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping&gt; ExitCodeRanges { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping&gt; ExitCodeRanges" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ExitConditions.ExitCodeRanges" />
      <MemberSignature Language="VB.NET" Value="Public Property ExitCodeRanges As IList(Of ExitCodeRangeMapping)" />
      <MemberSignature Language="F#" Value="member this.ExitCodeRanges : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ExitConditions.ExitCodeRanges" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="exitCodeRanges")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはタスクの範囲の終了コードと、バッチ サービスがそれらに応答する方法の一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitCodes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping&gt; ExitCodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping&gt; ExitCodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ExitConditions.ExitCodes" />
      <MemberSignature Language="VB.NET" Value="Public Property ExitCodes As IList(Of ExitCodeMapping)" />
      <MemberSignature Language="F#" Value="member this.ExitCodes : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ExitConditions.ExitCodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="exitCodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または個々 のタスクの終了コードと、バッチ サービスがそれらに応答する方法の一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileUploadError">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ExitOptions FileUploadError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.ExitOptions FileUploadError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ExitConditions.FileUploadError" />
      <MemberSignature Language="VB.NET" Value="Public Property FileUploadError As ExitOptions" />
      <MemberSignature Language="F#" Value="member this.FileUploadError : Microsoft.Azure.Batch.Protocol.Models.ExitOptions with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ExitConditions.FileUploadError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="fileUploadError")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ExitOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはファイルのアップロード エラーが発生した場合、バッチ サービスの応答方法を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            ExitCodes または exitCodeRanges で指定したが、ファイルのアップロード エラーが発生し、終了コードで、タスクが終了した場合、終了コードで指定されたアクションが優先されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PreProcessingError">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ExitOptions PreProcessingError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.ExitOptions PreProcessingError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ExitConditions.PreProcessingError" />
      <MemberSignature Language="VB.NET" Value="Public Property PreProcessingError As ExitOptions" />
      <MemberSignature Language="F#" Value="member this.PreProcessingError : Microsoft.Azure.Batch.Protocol.Models.ExitOptions with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ExitConditions.PreProcessingError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="preProcessingError")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ExitOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはエラーのため開始するタスクが失敗した場合、バッチ サービスの応答方法を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>