<Type Name="MigrationCommonModelFormatter" FullName="Microsoft.WindowsAzure.Management.StorSimple.MigrationCommonModelFormatter">
  <TypeSignature Language="C#" Value="public class MigrationCommonModelFormatter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MigrationCommonModelFormatter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.MigrationCommonModelFormatter" />
  <TypeSignature Language="VB.NET" Value="Public Class MigrationCommonModelFormatter" />
  <TypeSignature Language="F#" Value="type MigrationCommonModelFormatter = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MigrationCommonModelFormatter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationCommonModelFormatter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConcatStringList">
      <MemberSignature Language="C#" Value="public string ConcatStringList (System.Collections.Generic.List&lt;string&gt; stringList, string delimiter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string ConcatStringList(class System.Collections.Generic.List`1&lt;string&gt; stringList, string delimiter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationCommonModelFormatter.ConcatStringList(System.Collections.Generic.List{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ConcatStringList (stringList As List(Of String), Optional delimiter As String = null) As String" />
      <MemberSignature Language="F#" Value="member this.ConcatStringList : System.Collections.Generic.List&lt;string&gt; * string -&gt; string" Usage="migrationCommonModelFormatter.ConcatStringList (stringList, delimiter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stringList" Type="System.Collections.Generic.List&lt;System.String&gt;" />
        <Parameter Name="delimiter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="stringList">連結する文字列の一覧</param>
        <param name="delimiter">モノクロの個々 の文字列を区切り記号</param>
        <summary>
            Concats すべて文字列リスト区切りで指定された区切り記号で指定されました。
            </summary>
        <returns>リスト内の文字列を連結して形成される単一の文字列</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FormatTimeSpan">
      <MemberSignature Language="C#" Value="public string FormatTimeSpan (TimeSpan span);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string FormatTimeSpan(valuetype System.TimeSpan span) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationCommonModelFormatter.FormatTimeSpan(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function FormatTimeSpan (span As TimeSpan) As String" />
      <MemberSignature Language="F#" Value="member this.FormatTimeSpan : TimeSpan -&gt; string" Usage="migrationCommonModelFormatter.FormatTimeSpan span" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="span" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="span">表示する時間間隔</param>
        <summary>
            Timespan を書式設定します。
            </summary>
        <returns>文字列の形式の時間の長さ</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetResultMessage">
      <MemberSignature Language="C#" Value="public string GetResultMessage (string successMsg, Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus status);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetResultMessage(string successMsg, class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus status) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationCommonModelFormatter.GetResultMessage(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetResultMessage (successMsg As String, status As MigrationJobStatus) As String" />
      <MemberSignature Language="F#" Value="member this.GetResultMessage : string * Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus -&gt; string" Usage="migrationCommonModelFormatter.GetResultMessage (successMsg, status)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="successMsg" Type="System.String" />
        <Parameter Name="status" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus" />
      </Parameters>
      <Docs>
        <param name="successMsg">To be added.</param>
        <param name="status">移行ジョブの状態</param>
        <summary>
            サービスから取得したエラーの文字列で表示されることを確認して移行の成功メッセージを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HcsMessageInfoToString">
      <MemberSignature Language="C#" Value="public string HcsMessageInfoToString (Microsoft.WindowsAzure.Management.StorSimple.Models.HcsMessageInfo msgInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string HcsMessageInfoToString(class Microsoft.WindowsAzure.Management.StorSimple.Models.HcsMessageInfo msgInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationCommonModelFormatter.HcsMessageInfoToString(Microsoft.WindowsAzure.Management.StorSimple.Models.HcsMessageInfo)" />
      <MemberSignature Language="VB.NET" Value="Public Function HcsMessageInfoToString (msgInfo As HcsMessageInfo) As String" />
      <MemberSignature Language="F#" Value="member this.HcsMessageInfoToString : Microsoft.WindowsAzure.Management.StorSimple.Models.HcsMessageInfo -&gt; string" Usage="migrationCommonModelFormatter.HcsMessageInfoToString msgInfo" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="msgInfo" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.HcsMessageInfo" />
      </Parameters>
      <Docs>
        <param name="msgInfo">メッセージ情報 o/p</param>
        <summary>
            HcsMessageInfo を目的の文字列の出力に変換します。
            </summary>
        <returns>文字列を表示します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IntendAndConCat">
      <MemberSignature Language="C#" Value="public string IntendAndConCat (string prefix, object suffix, int maxLength = -1, string delimiter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string IntendAndConCat(string prefix, object suffix, int32 maxLength, string delimiter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationCommonModelFormatter.IntendAndConCat(System.String,System.Object,System.Int32,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function IntendAndConCat (prefix As String, suffix As Object, Optional maxLength As Integer = -1, Optional delimiter As String = null) As String" />
      <MemberSignature Language="F#" Value="member this.IntendAndConCat : string * obj * int * string -&gt; string" Usage="migrationCommonModelFormatter.IntendAndConCat (prefix, suffix, maxLength, delimiter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="suffix" Type="System.Object" />
        <Parameter Name="maxLength" Type="System.Int32" />
        <Parameter Name="delimiter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="prefix">サフィックス オブジェクトの名前</param>
        <param name="suffix">オブジェクトの文字列に変換する必要があります。</param>
        <param name="maxLength">maxlength するプレフィックスを indentented をする必要があります。</param>
        <param name="delimiter">プレフィックスとオブジェクトのサフィックスの間の区切り記号</param>
        <summary>
            API が使用される Concats に適切なインデント モノクロ文字列の区切り記号で区切られている、指定したオブジェクトのプレフィックスと文字列形式を
            </summary>
        <returns>プレフィックスとサフィックスを連結して形成される文字列</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>