<Type Name="ExitConditions" FullName="Microsoft.Azure.Batch.ExitConditions">
  <TypeSignature Language="C#" Value="public class ExitConditions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExitConditions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.ExitConditions" />
  <TypeSignature Language="VB.NET" Value="Public Class ExitConditions" />
  <TypeSignature Language="F#" Value="type ExitConditions = class&#xA;    interface ITransportObjectProvider&lt;ExitConditions&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            バッチ サービスの応答方法、タスクが完了したときにします。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExitConditions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ExitConditions.#ctor" />
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
            <see cref="T:Microsoft.Azure.Batch.ExitConditions" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Default">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ExitOptions Default { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.ExitOptions Default" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ExitConditions.Default" />
      <MemberSignature Language="VB.NET" Value="Public Property Default As ExitOptions" />
      <MemberSignature Language="F#" Value="member this.Default : Microsoft.Azure.Batch.ExitOptions with get, set" Usage="Microsoft.Azure.Batch.ExitConditions.Default" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ExitOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはその他のプロパティのいずれかでカバーされない終了条件によって、タスクが失敗した場合、バッチ サービスの応答方法を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            タスクが記載されていない 0 以外の終了コードで終了した場合、この値は使用、<see cref="P:Microsoft.Azure.Batch.ExitConditions.ExitCodes" />または<see cref="P:Microsoft.Azure.Batch.ExitConditions.ExitCodeRanges" />プリプロセス エラーのコレクション場合、<see cref="P:Microsoft.Azure.Batch.ExitConditions.PreProcessingError" />プロパティが、存在しないか、またはファイルを使用してアップロード失敗場合、<see cref="P:Microsoft.Azure.Batch.ExitConditions.FileUploadError" />プロパティは使用されません存在します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitCodeRanges">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ExitCodeRangeMapping&gt; ExitCodeRanges { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.ExitCodeRangeMapping&gt; ExitCodeRanges" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ExitConditions.ExitCodeRanges" />
      <MemberSignature Language="VB.NET" Value="Public Property ExitCodeRanges As IList(Of ExitCodeRangeMapping)" />
      <MemberSignature Language="F#" Value="member this.ExitCodeRanges : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ExitCodeRangeMapping&gt; with get, set" Usage="Microsoft.Azure.Batch.ExitConditions.ExitCodeRanges" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ExitCodeRangeMapping&gt;</ReturnType>
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
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ExitCodeMapping&gt; ExitCodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.ExitCodeMapping&gt; ExitCodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ExitConditions.ExitCodes" />
      <MemberSignature Language="VB.NET" Value="Public Property ExitCodes As IList(Of ExitCodeMapping)" />
      <MemberSignature Language="F#" Value="member this.ExitCodes : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ExitCodeMapping&gt; with get, set" Usage="Microsoft.Azure.Batch.ExitConditions.ExitCodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ExitCodeMapping&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはタスクの終了コードと、バッチ サービスがそれらに応答する方法の一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileUploadError">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ExitOptions FileUploadError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.ExitOptions FileUploadError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ExitConditions.FileUploadError" />
      <MemberSignature Language="VB.NET" Value="Public Property FileUploadError As ExitOptions" />
      <MemberSignature Language="F#" Value="member this.FileUploadError : Microsoft.Azure.Batch.ExitOptions with get, set" Usage="Microsoft.Azure.Batch.ExitConditions.FileUploadError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ExitOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはファイルのアップロード エラーが発生した場合、バッチ サービスの応答方法を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            使用して指定された終了コードで、タスクが終了している<see cref="P:Microsoft.Azure.Batch.ExitConditions.ExitCodes" />または<see cref="P:Microsoft.Azure.Batch.ExitConditions.ExitCodeRanges" />、し、ファイルのアップロード エラーが発生し、終了コードで指定された操作が優先されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PreProcessingError">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ExitOptions PreProcessingError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.ExitOptions PreProcessingError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ExitConditions.PreProcessingError" />
      <MemberSignature Language="VB.NET" Value="Public Property PreProcessingError As ExitOptions" />
      <MemberSignature Language="F#" Value="member this.PreProcessingError : Microsoft.Azure.Batch.ExitOptions with get, set" Usage="Microsoft.Azure.Batch.ExitConditions.PreProcessingError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ExitOptions</ReturnType>
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