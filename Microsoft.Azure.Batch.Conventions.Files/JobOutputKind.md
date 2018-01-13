<Type Name="JobOutputKind" FullName="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind">
  <TypeSignature Language="C#" Value="public sealed class JobOutputKind : IEquatable&lt;Microsoft.Azure.Batch.Conventions.Files.JobOutputKind&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit JobOutputKind extends System.Object implements class System.IEquatable`1&lt;class Microsoft.Azure.Batch.Conventions.Files.JobOutputKind&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class JobOutputKind&#xA;Implements IEquatable(Of JobOutputKind)" />
  <TypeSignature Language="F#" Value="type JobOutputKind = class&#xA;    interface IEquatable&lt;JobOutputKind&gt;&#xA;    interface IOutputKind" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.Azure.Batch.Conventions.Files.JobOutputKind&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            メイン ジョブの出力、またはジョブの出力のプレビューなど、ジョブの出力のカテゴリを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Custom">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Conventions.Files.JobOutputKind Custom (string text);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Conventions.Files.JobOutputKind Custom(string text) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.Custom(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Custom (text As String) As JobOutputKind" />
      <MemberSignature Language="F#" Value="static member Custom : string -&gt; Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" Usage="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.Custom text" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Conventions.Files.JobOutputKind</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="text" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="text">カスタム JobOutputKind のテキストの識別子です。</param>
        <summary>
            取得、<see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />ジョブ出力のカスタム カテゴリを表すです。
            </summary>
        <returns>指定されたテキストで JobOutputKind です。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="text" /> が null です。</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="text" /> が空です。</exception>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.Azure.Batch.Conventions.Files.JobOutputKind other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.Azure.Batch.Conventions.Files.JobOutputKind other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.Equals(Microsoft.Azure.Batch.Conventions.Files.JobOutputKind)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As JobOutputKind) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.Azure.Batch.Conventions.Files.JobOutputKind -&gt; bool" Usage="jobOutputKind.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />
      </Parameters>
      <Docs>
        <param name="other">このインスタンスと比較する JobOutputKind です。</param>
        <summary>
            このインスタンスと別に指定されているかどうかを determinates<see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />値が同じであります。
            </summary>
        <returns>true の場合の値、<paramref name="other" />パラメーターは、このインスタンスの値と同じです。 それ以外の場合は false。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="jobOutputKind.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj">現在のオブジェクトと比較するオブジェクト。</param>
        <summary>
            指定したオブジェクトが、現在のオブジェクトと等しいかどうかを判断します。
            </summary>
        <returns>指定したオブジェクトが現在のオブジェクトと等しい場合は true。それ以外の場合は false です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="jobOutputKind.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            この <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" /> のハッシュ コードを返します。
            </summary>
        <returns>32 ビット符号付き整数ハッシュ コード。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobOutput">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Batch.Conventions.Files.JobOutputKind JobOutput;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Batch.Conventions.Files.JobOutputKind JobOutput" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobOutput" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly JobOutput As JobOutputKind " />
      <MemberSignature Language="F#" Value=" staticval mutable JobOutput : Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" Usage="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobOutput" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Conventions.Files.JobOutputKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            A<see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />メイン ジョブの出力を表すです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobPreview">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Batch.Conventions.Files.JobOutputKind JobPreview;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Batch.Conventions.Files.JobOutputKind JobPreview" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobPreview" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly JobPreview As JobOutputKind " />
      <MemberSignature Language="F#" Value=" staticval mutable JobPreview : Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" Usage="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobPreview" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Conventions.Files.JobOutputKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            A<see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />ジョブ出力のプレビューを表すです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Equality">
      <MemberSignature Language="C#" Value="public static bool operator == (Microsoft.Azure.Batch.Conventions.Files.JobOutputKind x, Microsoft.Azure.Batch.Conventions.Files.JobOutputKind y);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Equality(class Microsoft.Azure.Batch.Conventions.Files.JobOutputKind x, class Microsoft.Azure.Batch.Conventions.Files.JobOutputKind y) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.op_Equality(Microsoft.Azure.Batch.Conventions.Files.JobOutputKind,Microsoft.Azure.Batch.Conventions.Files.JobOutputKind)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator == (x As JobOutputKind, y As JobOutputKind) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( = ) : Microsoft.Azure.Batch.Conventions.Files.JobOutputKind * Microsoft.Azure.Batch.Conventions.Files.JobOutputKind -&gt; bool" Usage="x = y" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="x" Type="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />
        <Parameter Name="y" Type="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />
      </Parameters>
      <Docs>
        <param name="x">比較する最初の JobOutputKind します。</param>
        <param name="y">比較する 2 番目の JobOutputKind します。</param>
        <summary>
            指定した 2 つあるかどうかを判断<see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />インスタンスが同じ値を設定します。
            </summary>
        <returns>true の場合の値<paramref name="x" />はの値と同じ<paramref name="y" />。 それ以外の場合は false。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Inequality">
      <MemberSignature Language="C#" Value="public static bool operator != (Microsoft.Azure.Batch.Conventions.Files.JobOutputKind x, Microsoft.Azure.Batch.Conventions.Files.JobOutputKind y);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Inequality(class Microsoft.Azure.Batch.Conventions.Files.JobOutputKind x, class Microsoft.Azure.Batch.Conventions.Files.JobOutputKind y) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.op_Inequality(Microsoft.Azure.Batch.Conventions.Files.JobOutputKind,Microsoft.Azure.Batch.Conventions.Files.JobOutputKind)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator != (x As JobOutputKind, y As JobOutputKind) As Boolean" />
      <MemberSignature Language="F#" Value="static member op_Inequality : Microsoft.Azure.Batch.Conventions.Files.JobOutputKind * Microsoft.Azure.Batch.Conventions.Files.JobOutputKind -&gt; bool" Usage="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.op_Inequality (x, y)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="x" Type="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />
        <Parameter Name="y" Type="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />
      </Parameters>
      <Docs>
        <param name="x">比較する最初の JobOutputKind します。</param>
        <param name="y">比較する 2 番目の JobOutputKind します。</param>
        <summary>
            指定した 2 つあるかどうかを判断<see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />インスタンスが異なる値を設定します。
            </summary>
        <returns>true の場合の値<paramref name="x" />の値とは異なる<paramref name="y" />。 それ以外の場合は false。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="jobOutputKind.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            現在のオブジェクトを表す文字列を返します。
            </summary>
        <returns><see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" /> のテキスト表現。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>